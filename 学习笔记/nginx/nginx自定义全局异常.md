## nginx自定义全局异常



```
 location / {
            proxy_pass http://lbs;
            proxy_redirect default;
           
            # 存放用户的真实ip
            proxy_set_header Host $host;
            proxy_set_header X-Real-IP $remote_addr;  
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;  
            
            proxy_next_upstream error timeout http_503 non_idempotent;

            #开启错误拦截配置,一定要开启
            proxy_intercept_errors on;
  }

# 不加 =200，则返回的就是原先的http错误码；配上后如果出现500等错误都返回给用户200状态，并跳转至/default_api
  error_page  404 500 502 503 504  =200  /default_api;
  location = /default_api {
    default_type application/json;
    #自定义返回结果
    return 200 '{"code":"-1","msg":"invoke fail, not found "}';
 }
```

- `proxy_next_upstream`用于指定在什么情况下Nginx会将请求转移到其他服务器上。其默认值是`proxy_next_upstream error timeout`，即发生网络错误以及超时，才会重试其他服务器。