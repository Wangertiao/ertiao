```
#user  nobody;
worker_processes  1;

#error_log  logs/error.log;
#error_log  logs/error.log  notice;
#error_log  logs/error.log  info;

#pid        logs/nginx.pid;


events {
    use epoll;
    worker_connections  1024;
}


http {
    include       mime.types;
    default_type  application/octet-stream;

    #log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
    #                  '$status $body_bytes_sent "$http_referer" '
    #                  '"$http_user_agent" "$http_x_forwarded_for"';

    #access_log  logs/access.log  main;

    sendfile        on;
    #tcp_nopush     on;

    #keepalive_timeout  0;
    keepalive_timeout  65;

    #gzip  on;
    upstream lbs {
       server 172.30.110.182:8089;
       server 172.30.110.182:8088;
    }
proxy_cache_path /root/cache levels=1:2 keys_zone=xd_cache:10m max_size=1g inactive=60m use_temp_path=off;
     server {
         listen       80;
         server_name  web.ertiao.xyz;
        #第一种跳转到https方法
         return 301 https://web.ertiao.xyz$request_uri;
        #第二种跳转方法
        # if  ($host =  "web.ertiao.xyz" ) {
         #      rewrite ^/(.*)$ https: //web.ertiao.xyz permanent;
        # }     

		}


    # HTTPS server
    #
    server {

        listen       443 ssl;
        server_name  web.ertiao.xyz;


        ssl_certificate      /usr/local/software/SSL_HTTPS/webertiaoxyz.pem;
        ssl_certificate_key    /usr/local/software/SSL_HTTPS/webertiaoxyz.key;

        ssl_session_cache    shared:SSL:1m;
        ssl_session_timeout  5m;

        ssl_ciphers  HIGH:!aNULL:!MD5;

     location /api/ {
        #代理路径
            proxy_pass http://lbs;
        #代理策略
            proxy_redirect default;
        #nginx代理时会改变请求信息 加上下面的就不会改变
            proxy_set_header Host $host:$server_port;
            proxy_set_header X-Real-IP $remote_addr;
            proxy_set_header X-Real-PORT $remote_port;
            proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
           #开启异常处理
             proxy_intercept_errors on;
      }
      
            location / {
                root   /usr/local/software/front_end/dist;
                index  index.html index.htm;
                proxy_set_header Host $host:$server_port;
                 proxy_set_header X-Real-IP $remote_addr;
                 proxy_set_header X-Real-PORT $remote_port;
                 proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;

                proxy_intercept_errors on;
            }
        #对异常进行处理
        error_page   500 502 503 504 404 =200  /default_api;
         location = /default_api {
             default_type application/json;
             return 200 '{"code":"-12321","msg":"nginx all Expection“}';
         }

    }

}


```

