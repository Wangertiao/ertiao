## Linux搭建nginx与前后端分离项目转发设置

## **1**、打开http://nginx.org/en/download.html 下载最新的包

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220525161815635.png" alt="image-20220525161815635" style="zoom:50%;" /> 



## 2、通过传输文件工具上传到云服务器

- MAC推荐 filezilla [filezilla下载地址](https://filezilla-project.org/)
- WIN推荐 winscp

## 3、上传到自己喜欢的位置

- 我这里上传到了/usr/local/software

## 4、解压nginx包

```
tar -zxvf nginx-1.21.6.tar.gz 
```

## 5、进入到解压好的文件夹下分别执行下面代码

```
(我解压好的目录并且改名为nginx：当前路径 /usr/local/software/nginx)

//安装gcc依赖
yum -y install gcc zlib zlib-devel pcre-devel openssl openssl-devel
//执行命令 如果需要https访问就这样配  不需要直接./configure
./configure --prefix=/usr/local/nginx --with-http_stub_status_module --with-http_ssl_module

make

make install 
//执行下面命令检查是否安装成功
/usr/local/nginx/sbin/nginx -V
用nginx 默认的配置会在https访问时响应头会返回一个server ：nginx 如果不想暴露是什么服务进行下面配置 在解压的生成的目录下执行 (防止恶意着利用nginx漏洞攻击）
vi src/http/ngx_http_header_filter_module.c
#49-50行修改
原内容：
static char ngx_http_server_string[] = "Server: nginx" CRLF;
static char ngx_http_server_full_string[] = "Server: " NGINX_VER CRLF;
 
更改为：
static char ngx_http_server_string[] = "Server: Xacp-Web" CRLF;
static char ngx_http_server_full_string[] = "Server: Xacp-Web " CRLF;
这样配置后https请求后响应头 server：Xacp-web 
```

![img](https://www.ertiao.co/wp-content/uploads/2022/05/image-1-1024x564.png)

- 默认安装到 /usr/local/nginx
- nginx常用命令

```
./nginx  #默认配置文件启动

./nginx -s reload #重启，加载默认配置文件

./nginx -c /usr/local/nginx/conf/nginx.conf #启动指定某个配置文件

./nginx -s stop #停止

#关闭进程，nginx有master process 和worker process,关闭master即可
ps -ef | grep "nginx" 
kill -9 PID 
```

## 6、配置nginx config文件

```
cd /usr/local/nginx/conf

vim nginx.conf 
```

**打开后是这样的**我把需要改动的地方列了出来

```
http {
    
   #内部转发一定要在server上方
    upstream lbs {
   #172.30.110.182是本机的私网ip地址 8089和8088是java运行的端口号（集群部署的）
       server 172.30.110.182:8089;
       server 172.30.110.182:8088;
    }

    server {
        listen       80;
        server_name  localhost;

        #此处省略 因为不需要改动 主要讲的是https
    }
    # https server
    #
    server {
        listen       443 ssl;
       #自己的域名
        server_name  web.ertiao.xyz;
       #阿里云申请的ssl证书下载nginx会给一个.pem和一个.key文件
        ssl_certificate      /usr/local/software/ssl_https/webertiaoxyz.pem;
        ssl_certificate_key    /usr/local/software/ssl_https/webertiaoxyz.key;

        ssl_session_cache    shared:ssl:1m;
        ssl_session_timeout  5m;

        ssl_ciphers  high:!anull:!md5;
        ssl_prefer_server_ciphers  on;
    #如果访问格式为https://web.ertiao.xyz/api/xxxxx访问的那么就会跳转到 upstream lbs里面定义的路径
     location /api/ {
            proxy_pass http://lbs;
            proxy_redirect default;
      }
     #如果是https://web.ertiao.xyz那么会跳转到项目的路径 
      location / {
               #root固定格式 后面放项目路径
                root   /usr/local/software/front_end/dist;
               #会默认找index.html找不到一次往后寻找
                index  index.html index.htm;
            }
    }

}
```

注意：这里主要讲解配置https访问以及转发

- 你们打开后https server下面的代码是注释的 需要取消注释
- server_name 后添加自己的域名
- 首先配置这两个路径 是在阿里云申请免费证书后下载nginx文件 ssl_certificate ssl_certificate_key
- 通过filezilla 上到指定位置 我这里上传到了/usr/local/software/SSL_HTTPS 位置

## 7、转发的实现

- nginx 通过upstream 进行内部转发