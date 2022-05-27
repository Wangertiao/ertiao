### Nginx经典案例挖掘accessLog日志

 

#### 第1集 你知道的Nginx访问日志的用处不？

**简介：介绍nginx的访问日志的用处**

- access.log日志用处
  - 统计站点访问ip来源、某个时间段的访问频率
  - 查看访问最频的页面、Http响应状态码、接口性能
  - 接口秒级访问量、分钟访问量、小时和天访问量
  - ...
- 默认配置解析



```
#log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
#                  '$status $body_bytes_sent "$http_referer" '
#                  '"$http_user_agent" "$http_x_forwarded_for"';
```

- 案例

```
122.70.148.18 - - [04/Aug/2020:14:46:48 +0800] "GET /user/api/v1/product/order/query_state?product_id=1&token=xdclasseyJhbGciOJE HTTP/1.1" 200 48 "https://xdclass.net/" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.89 Safari/537.36"
```

- 解析

```
$remote_addr 对应的是真实日志里的122.70.148.18，即客户端的IP。

$remote_user 对应的是第二个中杠“-”，没有远程用户，所以用“-”填充。

［$time_local］对应的是[04/Aug/2020:14:46:48 +0800]。

“$request”对应的是"GET /user/api/v1/product/order/query_state?product_id=1&token=xdclasseyJhbGciOJE HTTP/1.1"。

$status对应的是200状态码，200表示正常访问。

$body_bytes_sent对应的是48字节，即响应body的大小。

“$http_referer” 对应的是”https://xdclass.net/“，若是直接打开域名浏览的时，referer就会没有值，为”-“。

“$http_user_agent” 对应的是”Mozilla/5.0 (Macintosh; Intel Mac OS X 10.12; rv:56.0) Gecko/20100101 Firefox/56.0”。

“$http_x_forwarded_for” 对应的是”-“或者空。
```



#### 第2集 案例实战之BAT大厂应用运维平台案例统计

**简介：Nginx统计站点访问量、高频url统计**

 

- 查看访问最频繁的前100个IP

```
awk '{print $1}' access_temp.log | sort -n |uniq -c | sort -rn | head -n 100
```

 

- 统计访问最多的url 前20名

```
cat access_temp.log |awk '{print $7}'| sort|uniq -c| sort -rn| head -20 | more
```

 

- 基础

  ```
  awk 是文本处理工具，默认按照空格切分，$N 是第切割后第N个，从1开始
  sort命令用于将文本文件内容加以排序，-n 按照数值排，-r 按照倒序来排
    案例的sort -n 是按照第一列的数值大小进行排序，从小到大，倒序就是 sort -rn
  uniq 去除重复出现的行列, -c 在每列旁边显示该行重复出现的次数。
  ```





 

#### 第3集 案例实战之自定义日志统计接口性能

**简介 自定义日志格式，统计接口响应耗时**

- 日志格式增加 **$request_time**

```
从接受用户请求的第一个字节到发送完响应数据的时间，即包括接收请求数据时间、程序响应时间、输出响应数据时间

$upstream_response_time：指从Nginx向后端建立连接开始到接受完数据然后关闭连接为止的时间

$request_time一般会比upstream_response_time大，因为用户网络较差，或者传递数据较大时，前者会耗时大很多
```

- 配置自定义日志格式

```
log_format  main  '$remote_addr - $remote_user [$time_local] "$request" '
                     '$status $body_bytes_sent "$http_referer" '
                      '"$http_user_agent" "$http_x_forwarded_for" $request_time';


server {
        listen       80;
        server_name  aabbcc.com;

        location / {
            root   /usr/local/nginx/html;
            index  xdclass.html;
        }
        #charset koi8-r;
        #
        access_log  logs/host.access.log  main;
}
```

- 统计耗时接口, 列出传输时间超过 2 秒的接口，显示前5条

```
cat time_temp.log|awk '($NF > 2){print $7}'|sort -n|uniq -c|sort -nr|head -5

备注：$NF 表示最后一列, awk '{print $NF}'
```