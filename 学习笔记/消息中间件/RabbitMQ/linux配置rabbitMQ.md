**简介：Docker安装RabbitMQ消息队列**

- 登录个人的Linux服务器

  - ssh root@10.211.55.13

- Docker安装RabbitMQ

  - 地址：https://hub.docker.com/_/rabbitmq/

  ```
  #拉取镜像
  ```

  ```
  docker pull rabbitmq:management
  
  docker run -d --hostname rabbit_host1 --name xd_rabbit -e RABBITMQ_DEFAULT_USER=admin -e RABBITMQ_DEFAULT_PASS=password -p 15672:15672 -p 5672:5672 rabbitmq:management
  ```
  
  ```
  #介绍
  ```
  
  ```
  -d 以守护进程方式在后台运行
  ```
  
  ```
  -p 15672:15672 management 界面管理访问端口
  ```
  
  ```
  -p 5672:5672 amqp 访问端口
  ```
  
  ```
  --name：指定容器名
  ```
  
  ```
  --hostname：设定容器的主机名，它会被写到容器内的 /etc/hostname 和 /etc/hosts，作为容器主机IP的别名，并且将显示在容器的bash中
  ```
  
  ```
  -e 参数
  ```
  
  ```
    RABBITMQ_DEFAULT_USER 用户名
  ```
  
  ```
    RABBITMQ_DEFAULT_PASS 密码
  ```
  
  ```
  
  ```
  
  ```
  
  ```
  
- 主要端口介绍

  ```
  4369 erlang 发现口
  ```

  
  
  ```
5672 client 端通信口
  ```
  
  

  ```
  15672 管理界面 ui 端口
  ```

  
  
  ```
25672 server 间内部通信口
  ```
  
   

- 访问管理界面

  - ip:15672

- 注意事项！！！！

  - Linux服务器检查防火墙是否关闭
  - 云服务器检查网络安全组是否开放端口

  ```
  CentOS 7 以上默认使用的是firewall作为防火墙
  查看防火墙状态
  firewall-cmd --state
  停止firewall
  systemctl stop firewalld.service
  禁止firewall开机启动
  systemctl disable firewalld.service
  ```