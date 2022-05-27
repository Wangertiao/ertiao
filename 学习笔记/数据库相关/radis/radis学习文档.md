

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣" 更多架构课程请访问 xdclass.net**

### 第一章 全方位Redis6.x之战超多案例+最佳实践专题课程介绍

#### 第1集 全方位Redis6.x之战超多案例+最佳实践专题课程介绍

**简介：讲解全方位Redis6.x之战专题课程介绍，课程适合人员和学后水平**

- 课程介绍
  - 本套课程 是**2021年全新录制，**从0到1讲解分布式缓存**Redis6.x**,多种核心数据结构，零基础掌握Redis6.X核心基础+**高级知识点。**
  - 不止讲解Redis核心数据结构，**超多案例实战**：**图形验证码/商品热点数据/日销榜单/电商购物车/用户画像/社交应用/积分实时榜单/多场景分页缓存**等，还整合当下新版热门框架**SpringBoot2.X+SpringCache**框架实战；

 

- 为什么要学习分布式缓存Redis6.X

- - 多数互联网公司里面用的技术栈，**高并发项目都离不开**
  - 在多数互联网公司中，Redis6.X占有率很高，
  - 谁在使用Redis

- - - 国外: Google、Facebook、亚⻢逊
    - 国内:阿里、腾讯、字节、百度 等

- - 高级工程师岗位面试都喜欢问Redis：**核心数据结构、高性能原因、key设计、热点key、淘汰算法**等
  - 可以作为公司内部培训技术分享必备知识，超多案例+高可用实战等

![image-20210422172135547](https://file.xdclass.net/note/2021/redis/img/image-20210422172135547.png)

- 如果你想成为下面的一种，则**这个课程是必备**

- - - **后端**开发工程师-**中高级工程师**
    - **技术leader**或者**架构师**
    - 高级前端**工程师**
    - **运维工程师（高可用搭建和运维）**
    - **高级测试工程师（白盒测试性能优化）**
    - 从传统软件公司过渡到互联网公司的人员

-  

- 课程技术技术栈和测试环境说明

  - JDK8或者JDK11+SpringBoot2.5+IDEA旗舰版+Redis6.2版本

   

- 学后水平

- - 零基础掌握分布式缓存Redis6.X应用场景+源码安装部署+可视化工具
  - 掌握核心**数据结构 String/List/Hash/Set/SortedSet+命名规范**
  - 玩转超多Reids6.X经典案例:

- - - 图**形验证码/商品热点数据/日销榜单/电商购物车/用户画像**
    - **社交应用/粉丝、好友、共同关注/积分实时榜单/多场景分页缓存等**

- - 玩转**SpringBoot2.X**整合Redis**多客户端Jedis+Lettcuce**
  - 轻量级缓存**SpringCache**+项目多场景使用+自定义配置实战+**Jmeter压测**

- - **高级篇**
  - 超多面试题，**缓存穿透、击穿、雪崩原理分析**+解决方案+热点Key知识
  - 实战+原理:**分布式锁实战**+Redis+Lua脚本最佳实践+高级面试题
  - 实战+原理:Redis6.X**持久化AOF、RDB实战**+优缺点+新版混合模式
  - 玩转Redis的监控+**key删除策略+多种内存淘汰算法**
  - 实战+原理：新版Redis6.X**高可用实战 一主二从读写分离**搭建
  - 实战+原理：Redis6.X哨兵**Sentinel集群+主从+SpringBoot项目**整合
  - 实战+原理：玩转Redis6.X**集群Cluster+数据分片+虚拟哈希槽实战**
  - 实战+原理：Redis6.X集群**三主三从 + 故障自动转移 + SpringBoot项目**整合
  - 玩转Redis6.X新特性**多线程、ACL、客户端缓存ClientSideCaching**等

 

- 学习形式
  - 视频讲解 + 文字笔记 + 原理分析 + 交互流程图
  - 配套源码 + 笔记 + 技术群答疑( 我答疑，联系客服进群)
  - 只要是我的课程和项目-我会一直维护下去，大家不用担心！！！

 

 

 

 

 

#### 第2集 全方位Redis6.x之战超多案例+最佳实践课程大纲速览

**简介：讲解全方位Redis6.x之战课程大纲**

- 课程学前基础
  - 有Linux+SpringBoot就行，不会的话我们有专题课程学习,联系客服小姐姐即可
- 目录大纲浏览
- 学习要求：
  - 课程有配套资料，如果有用到就会在对应章集的资料里面，如果自己操作的情况和视频不一样，仔细对比对比验证基本就可以发现问题了
  - Redis比较坑的点，就是配置多，然后没有比较好的编辑器，所以遇到和课程效果不一样的，建议看多几次 结合笔记里面的配置，网上的博文
  - 很多错误配置，就是配置少加了 英文分号 ; 或者用了中文的； 或者防火墙问题，或者配置多了空格等特殊字符。

- 保持谦虚好学、术业有专攻、在校的学生，有些知识掌握也比工作好几年掌握的人厉害

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第二章 高并发必备技术+新版分布式缓存Redis6安装

#### 第1集 高并发的必备两大“核技术”队列和缓存

**简介：高并发的必备两大“核技术”队列和缓存介绍**

- 什么是队列（MQ消息中间件）
  - 全称MessageQueue，主要是用于程序和程序直接通信，异步+解耦
  - 使用场景：
    - 核心应用
      - 解耦：订单系统-》物流系统
      - 异步：用户注册-》发送邮件，初始化信息
      - 削峰：秒杀、日志处理

- 什么是缓存

  - 程序经常要调用的对象存在内存中,方便其使用时可以快 速调用,不必去数据库或者其他持久化设备中查询
  - 主要 就是提高性能 DNS缓存、前端缓存、代理服务器缓存Nginx、应用程序缓存、数据库缓存

   

![image-20210405103445219](https://file.xdclass.net/note/2021/redis/img/image-20210405103445219.png)

 

 

 

 

 

 

 

 

 

#### 第2集 本地缓存和分布式缓存介绍+热点key的解决方案

**简介：介绍本地缓存和分布式缓存**

- 分布式缓存
  - 与应用分离的缓存组件或服务，与本地应用隔离一个独 立的应用，多个应用可直接的共享缓存
  - 常⻅的分布式缓存 Redis、Memcached等
- 本地缓存
  - 和业务程序一起的缓存，例如myabtis的一级或者二级 缓存，本地缓存自然是最快的，但是不能在多个节点共 享
  - 常⻅的本地缓存
    - ssm基础课程myabtis 一级缓存、 mybatis二级缓存;
    - 框架本身的缓存;
    - redis本地单机服 务;
    - ehchche
    - guava cache
    - Caffeine
- 选择本地缓存和分布式缓存
  - 和业务数据结合去选择 高并发项目里面一般都是有本地缓存和分布式缓存共同 存在的
  - 热点key的解决方案之一：避免带宽或者传输影响，本地缓存热点key数据，对于每次读请求，将首先检查key是否存在于本地缓存中，如果存在则直接返回，如果不存在再去访问分布式缓存的机器
    - 缓存中的某些Key对应的value存储在集群中一台机器，使得所有流量涌向同一机器，成为系统的瓶颈，无法通过增加机器容量来解决
    - 热卖商品、热点新闻、热点评论、大V明星结婚

![image-20210405104337479](https://file.xdclass.net/note/2021/redis/img/image-20210405104337479.png)

 

 

 

 

 

 

 

#### 第3集 什么是NosQL和Redis快速介绍

**简介：Nosql介绍和Reidis介绍**

- 什么是Redis

  - 属于NoSQL的一种 ( Not Only SQL )

    - 是不同于传统的关系数据库的数据库管理系统的统称
    - 其两者最重要的区别是NoSQL不使用SQL作为查询语言。
    - NoSQL数据存储可以不需要固定的表格模式
    - 键 - 值对存储，列存储，文档存储，图形数据库
    - NoSql：redis、memcached、mongodb、Hbase

  - 官网地址：https://redis.io/

    - 中文：http://www.redis.cn/

  - 一个开源的使用 ANSI C 语言编写、遵守 BSD 协议、支持网络、可基于内存、分布式、可选持久性的键值对(Key-Value)存储数据库，并提供多种语言的 API

  - 高性能：Redis能读的速度是110000次/s,写的速度是81000次/s

  - 内存中的数据结构存储系统，它可以用作数据库、缓存和消息中间件。 它支持多 种类型的数据结构，如 字符串（strings）、散列（hashes）、 列表（lists）、 集合（sets）、 有序集合（sorted sets）等

     

   

- 谁在使用Redis

  - 国外： Google、Facebook、亚马逊
  - 国内：阿里、腾讯、字节、百度
    - 大厂们都有一个习惯：基于Redis二次开发，比如阿里Tair

   

- 高级工程师岗位面试都喜欢问Redis

  - 特性：aof/rdb、高性能原因、key设计、热点key、淘汰算法
  - 功能实现：排行榜、购物车、社交关系(粉丝、关注)、Feed流、附近的商家、分布式锁等等

 

 

 

 

 

 

 

 

 

#### 第4集 阿里云Linux服务器选择和常用软件介绍

**简介：阿里云Linux服务器购买和常用软件介绍**

- 云厂商

  - 阿里云：https://www.aliyun.com/
  - 腾讯云：https://cloud.tencent.com/
  - 亚马逊云：https://aws.amazon.com/
  - 阿里云新用户地址（如果地址失效，联系我或者客服即可，1折）
    - https://www.aliyun.com/minisite/goods?userCode=r5saexap&share_source=copy_link

- 环境问题说明

  - 务必使用CentOS 7 以上版本，64位系统，不要在Windows系统操作！！！！

  - 尽量前面先使用阿里云部署

  - 大家本地用虚拟机记得也要CentOS 7.x系统

    - vmware

       

 

- 注意：谁都不能保证每个人-硬件组成-系统版本-虚拟机软件版本都一样
  - 出现问题，大家结合报错日志搜索博文解决
  - 少数同学 -Win7、Win8、Win10、Mac、虚拟机等等，可能存在兼容问题

![image-20210405121007100](https://file.xdclass.net/note/2021/redis/img/image-20210405121007100.png)

- 选购实操

 

- windows工具 putty，xshell, security CRT

  - 参考资料：
    - https://jingyan.baidu.com/article/e75057f210c6dcebc91a89dd.html
    - https://www.jb51.net/softjc/88235.html

- 苹果系统MAC ： 通过终端登录

  - ssh root@ip 回车后输入密码
  - ssh root@120.24.216.117

  

- linux图形操作工具（用于远程连接上传文件）

  - mac: filezilla
    - sftp://120.24.216.117
  - windows: winscp
  - 参考资料：https://jingyan.baidu.com/article/ed2a5d1f346fd409f6be179a.html



- 可以尝试自己通过百度进行找文档， 安装mysql jdk nginx maven git redis等，也可以看我们的课程 xdclass.net

 

 

 

 

 

 

 

 

 

 

 

#### 第5集 Linux服务器源码安装Redis6和相关依赖

**简介：Linux服务器源码安装Redis6和相关依赖**

- 源码安装Redis-上传到Linux服务（安装包在本章本集资料里面, 先安装升级gcc再编译，不然会有问题）

```
#安装gcc
yum install -y gcc-c++ autoconf automake

#centos7 默认的 gcc 默认是4.8.5,版本小于 5.3 无法编译,需要先安装gcc新版才能编译
gcc -v

#升级新版gcc，配置永久生效
yum -y install centos-release-scl
yum -y install devtoolset-9-gcc devtoolset-9-gcc-c++ devtoolset-9-binutils

scl enable devtoolset-9 bash  
echo "source /opt/rh/devtoolset-9/enable" >>/etc/profile 

#编译redis
cd redis
make

#安装到指定目录
mkdir -p /usr/local/redis

make PREFIX=/usr/local/redis install
```

 

- 安装编译redis6需要升级gcc，默认自带的gcc版本比较老
- 目录介绍
  - 配置文件
  - redis-server
  - redis-cli
  - 指定配置文件

 

 

 

 

 

 

 

 

 

 

 

#### 第6集 Linux服务器Docker安装+容器化部署Redis6

**简介：Linux服务器Docker安装+容器化部署Redis6**

- 如果没Docker基础，建议是学习专题视频，这个公司用的很多 * https://xdclass.net/#/coursedetail?video_id=45 * 链接失效的话，联系客服小姐姐

```
云计算+容器化是当下的主流，也是未来的趋势, docker就是可以快速部署启动应用
实现虚拟化，完整资源隔离，一次编写，四处运行
但有一定的限制，比如Docker是基于Linux 64bit的，无法在32bit的linux/Windows/unix环境下使用
*  Docker安装
安装并运行Docker。
yum install docker-io -y
systemctl start docker

检查安装结果。
docker info

启动使用Docker
systemctl start docker     #运行Docker守护进程
systemctl stop docker      #停止Docker守护进程
systemctl restart docker   #重启Docker守护进程

docker ps查看容器
docker stop 容器id

修改镜像仓库
vim /etc/docker/daemon.json
#改为下面内容，然后重启docker
{
"debug":true,"experimental":true,
"registry-mirrors":["https://pb5bklzr.mirror.aliyuncs.com","https://hub-mirror.c.163.com","https://docker.mirrors.ustc.edu.cn"]
}

#查看信息
docker info
```

- docker部署redis 并配置密码

```
如果访问不了，记得看防火墙/网络安全组端口是否开放
源码安装redis的话默认不能远程访问 docker安装redis可以远程访问
 
docker run -itd --name xdclass-redis -p 6379:6379 redis --requirepass 123456


-i 以交互模式运行容器，通常与 
-t 同时使用;
-d 后台运行容器，并返回容器ID;
```

 

 

 

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第三章 分布式缓存Redis6核心配置+可视化工具介绍

 

#### 第1集 分布式缓存Redis6常见核心配置讲解

**简介：分布式缓存Redis6常见核心配置讲解**

- 你现在必须要知道的配置

  - daemonize yes 配置后台运行，默认no
  - bind 绑定指定ip访问，0.0.0.0是不限制，配置多个ip例子 12.13.432.12 31.12.43.13 用空格隔开
  - port 端口号 默认6379
  - requirepass 密码配置
  - dbfilename 配置redis持久化文件名称
  - dir 配置redis持久化文件存储地址
  - save 配置redis持久化机制

- 创建目录

  - 日志 /usr/local/redis/log
  - 数据 /usr/local/redis/data
  - 配置文件 /usr/local/redis/conf

- 创建自定义配置文件 (使用自带的也行)

  ```
  #任何ip可以访问
  ```

  ```
  bind 0.0.0.0
  ```

  ```
  
  ```

  ```
  #守护进程
  ```

  ```
  daemonize yes
  ```

  ```
  
  ```

  ```
  #密码
  ```

  ```
  requirepass 123456
  ```

  ```
  
  ```

  ```
  #日志文件
  ```

  ```
  logfile "/usr/local/redis/log/redis.log"
  ```

  ```
  
  ```

  ```
  #持久化文件名称
  ```

  ```
  dbfilename xdclass.rdb
  ```

  ```
  
  ```

  ```
  #持久化文件存储路径
  ```

  ```
  dir /usr/local/redis/data
  ```

  ```
  
  ```

  ```
  #持久化策略, 10秒内有个1个key改动，执行快照
  ```

  ```
  save 10 1
  ```

   

- 启动redis指定配置文件

  ```
  ./redis-server ../conf/redis.conf
  ```

   

 

- 核心是防止机器被入侵挖矿
  - 项目大课训练营里面有讲，有兴趣的同学可以学
  - 地址：https://detail.tmall.com/item.htm?id=634842400121

 

 

 

 

#### 第2集 redis6可视化客户端安装使用实战+key命名规范

**简介：redis6可视化客户端安装使用实战+key命名规范**

- Linux服务器
  - 云服务器开放网络安全组
    - redis配置下复杂密码，防止被挖矿
  - 本地虚拟机记得关闭防火墙

 

- key命名规范

  - 方便管理+易读
  - 不要过长,本身key也占据空间
  - 冒号分割，不要有特殊字符(空格-引号-转义符)
  - 例子：业务名:表名:ID
    - product-service:produdct:1
    - user:sign:1

   

- 单机默认16个数据库，集群的话则没有这个概念，而是solt槽位

 

 

 

 

 

 

#### 第3集 懒人学习redis6在线工具介绍

**简介：懒人学习redis6在线工具介绍**

- 如果各种原因：系统不兼容、虚拟机安装失败、手头紧买不了云服务器，或者懒
- 在线工具学习: http://try.redis.io/

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第四章 分布式缓存Redis6常见数据结构+指令实战

 

#### 第1集 Redis6常见数据结构概览

**简介：Redis6常见数据结构概览**

- 数据结构多种多样，方便大家记忆，使用脑图的形式
- 中文文档：http://www.redis.cn/
- 整个脑图，等讲完全部内容后会在资料里面加

![image-20210407164637865](https://file.xdclass.net/note/2021/redis/img/image-20210407164637865.png)

 

 

 

 

 

 

 

#### 第2集 Redis6数据结构之String类型介绍和应用场景

**简介：Redis6数据结构之String类型介绍和应用场景**

- 数据结构介绍：
- 应用场景：验证码、计数器、订单重复提交、用户登录信息、商品详情
- 常用命令： set/get/increment/decrement/del

![image-20210408151059804](https://file.xdclass.net/note/2021/redis/img/image-20210408151059804.png)

 

 

 

 

 

#### 第3集 Redis6数据结构之List类型介绍和应用场景

**简介：Redis6数据结构之List类型介绍和应用场景**

- 数据结构介绍：双向链表，插入删除时间复杂度O(1)快,查找为O(n)慢

- 应用场景：简单队列、最新商品列表、评论列表

   

![image-20210408151018680](https://file.xdclass.net/note/2021/redis/img/image-20210408151018680.png)

 

 

 

 

#### 第4集 Redis6数据结构之List核心命令讲解

**简介：Redis6数据结构之List核心命令讲解**

 

 

 

 

 

#### 第5集 Redis6数据结构之Hash类型介绍和应用场景

**简介：Redis6数据结构之Hash类型介绍和应用场景**

- 数据结构介绍：

- 应用场景：购物车存储、用户对象

   

![image-20210408150936461](https://file.xdclass.net/note/2021/redis/img/image-20210408150936461.png)

 

 

 

#### 第6集 Redis6数据结构之Hash核心命令讲解

**简介：Redis6数据结构之Hash核心命令介绍**

 

 

 

 

 

 

 

#### 第7集 Redis6数据结构之Set类型介绍和应用场景+命令

**简介：Redis6数据结构之Set类型介绍和应用场景**

- 数学：差集、交集、并集

- 数据结构介绍：

- 应用场景：大数据里面的用户画像标签集合、社交应用里面的共同好有

   

![image-20210408150901015](https://file.xdclass.net/note/2021/redis/img/image-20210408150901015.png)

 

 

 

 

 

 

 

#### 第8集 Redis6数据结构之SortedSet类型介绍和跳跃表介绍

**简介：Redis6数据结构之SortedSet类型介绍和应用场景**

- 数据结构介绍：使用HashMap+跳表skipList保证数据存储和有序
- 应用场景：商品日销榜、积分榜等
- 什么是跳跃表：性能堪比红黑树，而且实现起来比红黑树简单很多

 

![image-20210408150830018](https://file.xdclass.net/note/2021/redis/img/image-20210408150830018.png)

 

 

 

 

 

#### 第9集 Redis6数据结构之SortedSet核心命令介绍

**简介：Redis6数据结构之SortedSet核心命令介绍**

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第五章 新版SpringBoot2.x整合Redis6客户端实战

 

#### 第1集 分布式缓存Redis客户端讲解

**简介：分布式缓存Redis客户端讲解**

- 自带客户端 redis-cli

- 可视化工具

- 语言客户端：java、nodejs、python

  - java语言客户端:

    - jedis

    ```
    Jedis 是直连模式，在多个线程间共享一个 Jedis 实例时是线程不安全的,需要使用连接池
    ```

    ```
    
    ```

    ```
    其API提供了比较全面的Redis命令的支持，相比于其他Redis 封装框架更加原生
    ```

    ```
    
    ```

    ```
    Jedis中的方法调用是比较底层的暴露的Redis的API，Java方法基本和Redis的API保持着一致
    ```

    ```
    
    ```

    ```
    使用阻塞的I/O，方法调用同步，程序流需要等到socket处理完I/O才能执行，不支持异步操作
    ```

    - lettuce

    ```
    高级Redis客户端，用于线程安全同步，异步响应
    ```

    ```
    
    ```

    ```
    基于Netty的的事件驱动，可以在多个线程间并发访问, 通过异步的方式可以更好的利用系统资源
    ```

   

 

 

 

 

 

 

 

 

 

#### 第2集 新版SpringBoot2.X项目创建

**简介：新版SpringBoot2.X项目创建**

- 新版SpringBoot2.X介绍
  - 官网：https://spring.io/projects/spring-boot
  - GitHub地址：https://github.com/spring-projects/spring-boot
  - 官方文档：https://spring.io/guides/gs/spring-boot/
  - 视频地址：https://item.taobao.com/item.htm?id=618384570391
- 相关软件环境和作用
  - JDK1.8+以上
  - Maven3.5+
  - 编辑器IDEA(旗舰版)
  - PostMan
  - 翻译神器
    - https://translate.google.cn/
- 在线创建 ：https://start.spring.io/
  - 注意：
    - 采用springboot2.5 + jdk11
    - 初次导入项目下载包比较慢 5~20分钟不等
      - 出问题的话: mvn clean install 试试
    - 不建议修改默认maven仓库（可以先还原默认的，防止下载包失败）
    - idea记得配置jdk11

 

 

 

 

 

 

 

#### 第3集SpringBoot2.x实战整合Redis客户端+单元测试

**简介：SpringBoot2.x整合Redis客户端+单元测试**

- 在SpringBoot整合Redis很简单

  - SpringData介绍
    - 操作mysql/redis/elasticseatch
    - SpringDataRedis是专门操作redis的依赖
  - 添加依赖 spring-boot-starter-data-redis

  ```
    <dependency>
  ```

  ```
        <groupId>org.springframework.boot</groupId>
  ```

  ```
        <artifactId>spring-boot-starter-data-redis</artifactId>
  ```

  ```
    </dependency>
  ```

   

- 注意

  - Springboot2后默认使用Lettuce作为访问redis的客户端
  - 旧版本lettuce存在堆外内存溢出的bug， 5.3版本修复了这个bug, 我们是用 6.1
  - 很多同学没产生原因
    - 并发量不高
    - 内存足够大，没发生问题就又发布更新了
  - 解决方式
    - 升级版本
    - 换jedis

   

 

 

 

 

 

 

 

 

 

#### 第4集 SpringDataRedis的RedisTemplate讲解介绍

**简介：SpringDataRedis配置RedisTemplate介绍**

- RedisTemplate介绍

  - ValueOperations：简单K-V操作
  - SetOperations：set类型数据操作
  - ZSetOperations：zset类型数据操作
  - HashOperations：针对map类型的数据操作
  - ListOperations：list类型的数据操作

- RedisTemplate和StringRedisTemplate的区别

  - StringRedisTemplate继承RedisTemplate
  - 两者的数据是不共通的（默认的序列化机制导致key不一样）
  - StringRedisTemplate默认采用的是String的序列化策略
  - RedisTemplate默认采用的是JDK的序列化策略，会将数据先序列化成字节数组然后在存入Redis数据库
  - 总结
    - 当redis数据库里面本来操作的是字符串数据的时候，那使用StringRedisTemplate即可
    - 数据是复杂的对象类型，那么使用RedisTemplate是更好的选择

- 操作

  - String结构

    - 存储字符串
    - 存储对象

     

 

 

 

 

 

#### 第5集 RedisTemplate的序列和反序列化机制讲解

**简介：RedisTemplate的序列和反序列化机制讲解**

- 上集问题
  - 同个key为啥获取不到值，核心就是序列化机制导致key不一样
- 什么是序列化
  - 把对象转换为字节序列的过程称为对象的序列化。
  - 把字节序列恢复为对象的过程称为对象的反序列化。
  - 对象的序列化主要有两种用途
    - 把对象的字节序列永久地保存到硬盘上，通常存放在一个文件中
    - 在网络上传送对象的字节序列。
- Redis为什么要序列化
  - 性能可以提高，不同的序列化方式性能不一样
  - 可视化工具更好查看
    - 采用默认的jdk方式会乱码（POJO类需要实现Serializable接口）
    - 采用JSON方式则不用，且可视化工具更好查看

 

- 自定义redis序列化方式，提供了多种可选择策略
  - JdkSerializationRedisSerializer
    - POJO对象的存取场景，使用JDK本身序列化机制
    - 默认机制 ObjectInputStream/ObjectOutputStream进行序列化操作
  - StringRedisSerializer
    - Key或者value为字符串
  - Jackson2JsonRedisSerializer
    - 利用jackson-json工具，将pojo实例序列化成json格式存储
  - GenericFastJsonRedisSerializer
    - 另一种javabean与json之间的转换，同时也需要指定Class类型
  - ...

![image-20210409150440389](https://file.xdclass.net/note/2021/redis/img/image-20210409150440389.png)

 

 

 

 

 

 

 

 

 

#### 第6集 RedisTemplate 序列化机制配置实战

**简介：自定义序列化和反序列化机制配置实战**

- 配置实战

```
@Configuration
public class RedisTemplateConfiguration {

    /**
     * @param redisConnectionFactory
     * @return
     */
    @Bean
    public RedisTemplate<Object, Object> redisTemplate(RedisConnectionFactory redisConnectionFactory) {

        RedisTemplate<Object, Object> redisTemplate = new RedisTemplate<>();
        redisTemplate.setConnectionFactory(redisConnectionFactory);

        // 使用Jackson2JsonRedisSerialize 替换默认序列化
        Jackson2JsonRedisSerializer jackson2JsonRedisSerializer = new Jackson2JsonRedisSerializer(Object.class);

        ObjectMapper objectMapper = new ObjectMapper();
        objectMapper.setVisibility(PropertyAccessor.ALL, JsonAutoDetect.Visibility.ANY);
        jackson2JsonRedisSerializer.setObjectMapper(objectMapper);

        // 设置key和value的序列化规则
        redisTemplate.setKeySerializer(new StringRedisSerializer());
        redisTemplate.setValueSerializer(jackson2JsonRedisSerializer);

        // 设置hashKey和hashValue的序列化规则
        redisTemplate.setHashKeySerializer(new StringRedisSerializer());
        redisTemplate.setHashValueSerializer(jackson2JsonRedisSerializer);

        // 设置支持事物
        //redisTemplate.setEnableTransactionSupport(true);

        redisTemplate.afterPropertiesSet();

        return redisTemplate;
    }

}
```

 

 

 

 

 

#### 第7集 SpringBoot整合Jedis+Lettuce客户端连接池配置实战

**简介：SpringBoot整合Jedis+Lettuce客户端连接池配置实战**

- 基于SpringDataRedis可以快速替换底层实现

  - Lettuce连接池介绍(添加连接池)

  ```
    <dependency>
  ```

  ```
        <groupId>org.apache.commons</groupId>
  ```

  ```
        <artifactId>commons-pool2</artifactId>
  ```

  ```
      </dependency>
  ```

  ```
  # 连接池最大连接数（使用负值表示没有限制）
  ```

  ```
  spring.redis.lettuce.pool.max-active = 10
  ```

  ```
  
  ```

  ```
  # 连接池中的最大空闲连接
  ```

  ```
  spring.redis.lettuce.pool.max-idle = 10
  ```

  ```
  
  ```

  ```
  # 连接池中的最小空闲连接
  ```

  ```
  spring.redis.lettuce.pool.min-idle = 0
  ```

  ```
  
  ```

  ```
  # 连接池最大阻塞等待时间（使用负值表示没有限制）
  ```

  ```
  spring.redis.lettuce.pool.max-wait= -1ms
  ```

  ```
  
  ```

  ```
  #指定客户端
  ```

  ```
  spring.redis.client-type = lettuce
  ```

   

   

  - Jedis连接池介绍（可以不排除lettuce依赖包）

  ```
    <dependency>
  ```

  ```
        <groupId>org.springframework.boot</groupId>
  ```

  ```
        <artifactId>spring-boot-starter-data-redis</artifactId>
  ```

  ```
        <exclusions>
  ```

  ```
          <exclusion>
  ```

  ```
            <groupId>io.lettuce</groupId>
  ```

  ```
            <artifactId>lettuce-core</artifactId>
  ```

  ```
          </exclusion>
  ```

  ```
        </exclusions>
  ```

  ```
      </dependency>
  ```

  ```
      
  ```

  ```
      <!--不用指定版本号，本身spring-data-redis里面有-->
  ```

  ```
      <dependency>
  ```

  ```
        <groupId>redis.clients</groupId>
  ```

  ```
        <artifactId>jedis</artifactId>
  ```

  ```
      </dependency>
  ```

  ```
      
  ```

  ```
  <dependency>
  ```

  ```
      <groupId>org.apache.commons</groupId>
  ```

  ```
        <artifactId>commons-pool2</artifactId>
  ```

  ```
        <version>2.6.1</version>
  ```

  ```
    </dependency>
  ```

   

  ```
  # 连接池最大连接数（使用负值表示没有限制）
  ```

  ```
  spring.redis.jedis.pool.max-active = 10
  ```

  ```
  
  ```

  ```
  # 连接池中的最大空闲连接
  ```

  ```
  spring.redis.jedis.pool.max-idle = 10
  ```

  ```
  
  ```

  ```
  # 连接池中的最小空闲连接
  ```

  ```
  spring.redis.jedis.pool.min-idle = 0
  ```

  ```
  
  ```

  ```
  # 连接池最大阻塞等待时间（使用负值表示没有限制）
  ```

  ```
  spring.redis.jedis.pool.max-wait= -1ms
  ```

  ```
  
  ```

  ```
  #指定客户端
  ```

  ```
  spring.redis.client-type = jedis
  ```

   

- 断点调试 redisTemplate的connectionFactory实现

![image-20210409180721998](https://file.xdclass.net/note/2021/redis/img/image-20210409180721998.png)

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第六章 分布式缓存实战-String数据结构最佳案例+Jmeter5.x压测

 

#### 第1集 案例实战需求之图形验证码+谷歌开源Kaptcha介绍

**简介：案例实战之注册登录-图形验证码+谷歌开源Kaptcha引入**

- 背景
  - 注册-登录-修改密码一般需要发送验证码，但是容易被攻击恶意调用
  - 什么是短信-邮箱轰炸机
    - 手机短信轰炸机是批􏰀、循环给手机无限发送各种网站的注册验 证码短信的方法。
  - 公司带来的损失
    - 短信一条5分钱，如果被大􏰀盗刷大家自己计算 邮箱通知不用钱，但被大􏰀盗刷，带宽、连接等都被占 用，导致无法正常使用
- 如何避免自己的网站成为”肉鸡“或者被刷呢
  - 增加图形验证码(开发人员)
  - 单IP请求次数限制(开发人员)
  - 限制号码发送(一般短信提供商会做)
  - 攻防永远是有的，只过加大了攻击者的成本，ROI划不 过来自然就放弃了
- Kaptcha 框架介绍
  - 谷歌开源的一个可高度配置的实用验证 码生成工具
    - 验证码的字体/大小/颜色
    - 验证码内容的范围(数字，字母，中文汉字!)
    - 验证码图片的大小，边框，边框粗细，边框颜色
    - 验证码的干扰线 验证码的样式(⻥眼样式、3D、普通模糊)
- 添加依赖

```
 <!--kaptcha依赖包--> 
<dependency>
      <groupId>com.baomidou</groupId>
      <artifactId>kaptcha-spring-boot-starter</artifactId>
      <version>1.0.0</version>
    </dependency>
```

- 代码配置

```
@Configuration
public class CaptchaConfig {

    /**
     * 验证码配置
     * Kaptcha配置类名
     * 
     * @return
     */
    @Bean
    @Qualifier("captchaProducer")
    public DefaultKaptcha kaptcha() {
        DefaultKaptcha kaptcha = new DefaultKaptcha();
        Properties properties = new Properties();
        //验证码个数
        properties.setProperty(Constants.KAPTCHA_TEXTPRODUCER_CHAR_LENGTH, "4");
        //字体间隔
        properties.setProperty(Constants.KAPTCHA_TEXTPRODUCER_CHAR_SPACE,"8");
        //干扰线颜色

        //干扰实现类
        properties.setProperty(Constants.KAPTCHA_NOISE_IMPL, "com.google.code.kaptcha.impl.NoNoise");

        //图片样式
        properties.setProperty(Constants.KAPTCHA_OBSCURIFICATOR_IMPL, "com.google.code.kaptcha.impl.WaterRipple");

        //文字来源
        properties.setProperty(Constants.KAPTCHA_TEXTPRODUCER_CHAR_STRING, "0123456789");
        Config config = new Config(properties);
        kaptcha.setConfig(config);
        return kaptcha;
    }
}
```

 

 

 

 

 

 

 

 

#### 第2集 案例实战之企业级-验证码存储Redis和工具类介绍

**简介：验证码存储Redis逻辑编码实战**

- CommonUtil工具类

```
    /**
     * 获取ip
     * @param request
     * @return
     */
    public static String getIpAddr(HttpServletRequest request) {
        String ipAddress = null;
        try {
            ipAddress = request.getHeader("x-forwarded-for");
            if (ipAddress == null || ipAddress.length() == 0 || "unknown".equalsIgnoreCase(ipAddress)) {
                ipAddress = request.getHeader("Proxy-Client-IP");
            }
            if (ipAddress == null || ipAddress.length() == 0 || "unknown".equalsIgnoreCase(ipAddress)) {
                ipAddress = request.getHeader("WL-Proxy-Client-IP");
            }
            if (ipAddress == null || ipAddress.length() == 0 || "unknown".equalsIgnoreCase(ipAddress)) {
                ipAddress = request.getRemoteAddr();
                if (ipAddress.equals("127.0.0.1")) {
                    // 根据网卡取本机配置的IP
                    InetAddress inet = null;
                    try {
                        inet = InetAddress.getLocalHost();
                    } catch (UnknownHostException e) {
                        e.printStackTrace();
                    }
                    ipAddress = inet.getHostAddress();
                }
            }
            // 对于通过多个代理的情况，第一个IP为客户端真实IP,多个IP按照','分割
            if (ipAddress != null && ipAddress.length() > 15) {
                // "***.***.***.***".length()
                // = 15
                if (ipAddress.indexOf(",") > 0) {
                    ipAddress = ipAddress.substring(0, ipAddress.indexOf(","));
                }
            }
        } catch (Exception e) {
            ipAddress="";
        }
        return ipAddress;
    }



    public static String MD5(String data)  {
        try {
            java.security.MessageDigest md = MessageDigest.getInstance("MD5");
            byte[] array = md.digest(data.getBytes("UTF-8"));
            StringBuilder sb = new StringBuilder();
            for (byte item : array) {
                sb.append(Integer.toHexString((item & 0xFF) | 0x100).substring(1, 3));
            }
            return sb.toString().toUpperCase();
        } catch (Exception exception) {
        }
        return null;

    }
```

- 接口开发

```
    
    @Autowired
    private StringRedisTemplate redisTemplate;

    @Autowired
    private Producer captchaProducer;

    /**
     *临时使用10分钟有效，方便测试
     */
    private static final long CAPTCHA_CODE_EXPIRED = 60 * 1000 * 10;

    /**
     * 获取图形验证码
     * @param request
     * @param response
     */
    @GetMapping("captcha")
    public void getCaptcha(HttpServletRequest request, HttpServletResponse response){

        String captchaText = captchaProducer.createText();

        //存储
        redisTemplate.opsForValue().set(getCaptchaKey(request),captchaText,CAPTCHA_CODE_EXPIRED,TimeUnit.MILLISECONDS);

        BufferedImage bufferedImage = captchaProducer.createImage(captchaText);
        ServletOutputStream outputStream = null;
        try {
            outputStream = response.getOutputStream();
            ImageIO.write(bufferedImage,"jpg",outputStream);
            outputStream.flush();
            outputStream.close();
        } catch (IOException e) {
        }

    }

    /**
     * 获取缓存的key
     * @param request
     * @return
     */
    private String getCaptchaKey(HttpServletRequest request){

        String ip = CommonUtils.getIpAddr(request);
        String userAgent = request.getHeader("User-Agent");

        String key = "user-service:captcha:"+CommonUtils.MD5(ip+userAgent);

        return key;

    }
```

 

 

 

 

 

 

 

#### 第3集 案例实战之JsonData工具类封装+验证码校验编码实战

**简介：JsonData工具类封装+验证码校验编码实战**

- JsonData响应工具类封装

```
public class JsonData {

    /**
     * 状态码 0 表示成功
     */

    private Integer code;
    /**
     * 数据
     */
    private Object data;
    /**
     * 描述
     */
    private String msg;


    public JsonData(int code,Object data,String msg){
        this.code = code;
        this.msg = msg;
        this.code = code;
    }

    /**
     * 成功，不传入数据
     * @return
     */
    public static JsonData buildSuccess() {
        return new JsonData(0, null, null);
    }

    /**
     *  成功，传入数据
     * @param data
     * @return
     */
    public static JsonData buildSuccess(Object data) {
        return new JsonData(0, data, null);
    }

    /**
     * 失败，传入描述信息
     * @param msg
     * @return
     */
    public static JsonData buildError(String msg) {
        return new JsonData(-1, null, msg);
    }
    
    //set get 方法省略
}
```

 

- 校验逻辑

```
    /**
     * 支持手机号、邮箱发送验证码
     * @return
     */
    @GetMapping("send_code")
    public JsonData sendRegisterCode(@RequestParam(value = "to", required = true)String to,
                                     @RequestParam(value = "captcha", required = true)String  captcha,
                                     HttpServletRequest request){

        String key = getCaptchaKey(request);
        String cacheCaptcha = redisTemplate.opsForValue().get(key);

        if(captcha!=null && cacheCaptcha!=null && cacheCaptcha.equalsIgnoreCase(captcha)) {
            redisTemplate.delete(key);
           //TODO 发送验证码
            return jsonData;
        }else {
            return JsonData.buildResult("图形验证码错误");
        }

    }
```

 

 

 

 

 

 

 

 

 

#### 第4集 小滴课堂官网-高并发下-商品首页热点数据开发实战

**简介：高并发商品首页热点数据开发实战**

- 热点数据

  - 经常会被查询，但是不经常被修改或者删除的数据
  - 首页-详情页

- 链路逻辑

  - 检查缓存是否有
  - 缓存不存在则查询数据库
  - 查询结果放到缓存，设置过期时间
  - 下次访问则命中缓存

- 接口开发

  - 模拟数据库查询耗时200ms
  - 未加缓存逻辑：controller-service-dao层
  - 加缓存逻辑：controller-service-dao层

   

- 注意点

  - 缓存击穿
  - 缓存穿透
  - 缓存雪崩
  - 缓存和数据库数据一致性

 

 

 

 

 

 

 

 

#### 第5集 一线大厂必备Jmeter5.x压力测试工具急速入门

**简介: 一线大厂必备Jmeter5.x压力测试工具急速入门**

- LoadRunner
  - 性能稳定，压测结果及细粒度大，可以自定义脚本进行压测，但是太过于重大，功能比较繁多
- Apache AB(单接口压测最方便)
  - 模拟多线程并发请求,ab命令对发出负载的计算机要求很低，既不会占用很多CPU，也不会占用太多的内存，但却会给目标服务器造成巨大的负载, 简单DDOS攻击等
- Webbench
  - webbench首先fork出多个子进程，每个子进程都循环做web访问测试。子进程把访问的结果通过pipe告诉父进程，父进程做最终的统计结果。
- Jmeter
  - 开源免费，功能强大，在互联网公司普遍使用
- 压测工具本地快速安装Jmeter5.x
  - 需要安装JDK8 以上
  - 建议安装JDK环境，虽然JRE也可以，但是压测https需要JDK里面的 keytool工具
  - 快速下载 https://jmeter.apache.org/download_jmeter.cgi
  - 文档地址：http://jmeter.apache.org/usermanual/get-started.html
- 目录

```
bin:核心可执行文件，包含配置
        jmeter.bat: windows启动文件(window系统一定要配置显示文件拓展名)
        jmeter: mac或者linux启动文件
        jmeter-server：mac或者Liunx分布式压测使用的启动文件
        jmeter-server.bat：window分布式压测使用的启动文件
        jmeter.properties: 核心配置文件   
extras：插件拓展的包

lib:核心的依赖包
```

- Jmeter语言版本中英文切换
  - 控制台修改 menu -> options -> choose language
- 配置文件修改
  - bin目录 -> jmeter.properties
  - 默认 #language=en
  - 改为 language=zh_CN

 

 

 

 

 

 

 

 

 

#### 第6集 Jmeter5.X基础功能组件介绍+线程组和Sampler

**简介：讲解Jmeter里面GUI菜单栏主要组件**

- 添加->threads->线程组（控制总体并发）

  ```
  线程数：虚拟用户数。一个虚拟用户占用一个进程或线程
  ```

  ```
  
  ```

  ```
  准备时长（Ramp-Up Period(in seconds)）：全部线程启动的时长，比如100个线程，20秒，则表示20秒内 100个线程都要启动完成，每秒启动5个线程
  ```

  ```
  
  ```

  ```
  循环次数：每个线程发送的次数，假如值为5，100个线程，则会发送500次请求，可以勾选永远循环
  ```

  

- 线程组->添加-> Sampler(采样器) -> Http （一个线程组下面可以增加几个Sampler）

  ```
  名称：采样器名称
  ```

  ```
  注释：对这个采样器的描述
  ```

  ```
  web服务器：
  ```

  ```
    默认协议是http
  ```

  ```
    默认端口是80
  ```

  ```
    服务器名称或IP ：请求的目标服务器名称或IP地址
  ```

  ```
  
  ```

  ```
  路径：服务器URL
  ```

  

- 查看测试结果

  ```
  线程组->添加->监听器->察看结果树
  ```

  ```
  线程组->添加->监听器->聚合报告
  ```

   

 

 

#### 第7集 Jmeter5.x压测接口实战-接口性能优化前后QPS对比

**简介： Jmeter5.x压测接口实战-接口性能优化前后QPS对比**

- 热点数据接口压测

  - QPS: (Query Per Second): 每秒请求数,就是说服务器在一秒的时间内处理了多少个请求

   

- 新增聚合报告：线程组->添加->监听器->聚合报告（Aggregate Report）

```
  lable: sampler的名称
  Samples: 一共发出去多少请求,例如10个用户，循环10次，则是 100
  Average: 平均响应时间
  Median: 中位数，也就是 50％ 用户的响应时间


  90% Line : 90％ 用户的响应不会超过该时间 （90% of the samples took no more than this time.     The remaining samples at least as long as this）
  95% Line : 95％ 用户的响应不会超过该时间
  99% Line : 99％ 用户的响应不会超过该时间
  min : 最小响应时间
  max : 最大响应时间

  

  Error%：错误的请求的数量/请求的总数
  Throughput： 吞吐量——默认情况下表示每秒完成的请求数（Request per Second) 可类比为qps、tps
  KB/Sec: 每秒接收数据量
```

- 基于当前机器配置压测
  - 未用缓存接口
  - 用缓存接口
- 当前架构存在的问题
  - 分布式缓存和应用服务器网络需要内网通信
  - 大家可以自己本地部署Redis进行测试

 

 

 

 

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第七章 【高级篇】分布式锁之Redis6+Lua脚本实现原生分布式锁

 

#### 第1集 分布式核心技术-关于高并发下分布式锁你知道多少？

**简介：分布式锁核心知识介绍和注意事项**

- 背景

  - 就是保证同一时间只有一个客户端可以对共享资源进行操作

  - 案例：优惠券领劵限制张数、商品库存超卖

  - 核心

    - 为了防止分布式系统中的多个进程之间相互干扰，我们需要一种分布式协调技术来对这些进程进行调度
    - 利用互斥机制来控制共享资源的访问，这就是分布式锁要解决的问题

     

- 避免共享资源并发操作导致数据问题

  - 加锁
    - 本地锁：synchronize、lock等，锁在当前进程内，集群部署下依旧存在问题
    - 分布式锁：redis、zookeeper等实现，虽然还是锁，但是多个进程共用的锁标记，可以用Redis、Zookeeper、Mysql等都可以

![image-20210410164720650](https://file.xdclass.net/note/2021/redis/img/image-20210410164720650.png)

- 设计分布式锁应该考虑的东西
  - 排他性
    - 在分布式应用集群中，同一个方法在同一时间只能被一台机器上的一个线程执行
  - 容错性
    - 分布式锁一定能得到释放，比如客户端奔溃或者网络中断
  - 满足可重入、高性能、高可用
  - 注意分布式锁的开销、锁粒度

 

 

 

 

 

 

 

 

 

 

 

#### 第2集 基于Redis实现分布式锁的几种坑你是否踩过《上》

**简介：基于Redis实现分布式锁的几种坑**

- 实现分布式锁 可以用 Redis、Zookeeper、Mysql数据库这几种 , 性能最好的是Redis且是最容易理解
  - 分布式锁离不开 key - value 设置

```
key 是锁的唯一标识，一般按业务来决定命名，比如想要给一种优惠券活动加锁，key 命名为 “coupon:id” 。value就可以使用固定值，比如设置成1
```



- 基于redis实现分布式锁，文档：http://www.redis.cn/commands.html#string

  - 加锁 SETNX key value

  ```
  setnx 的含义就是 SET if Not Exists，有两个参数 setnx(key, value)，该方法是原子性操作
  ```

  ```
  
  ```

  ```
  如果 key 不存在，则设置当前 key 成功，返回 1；
  ```

  ```
  
  ```

  ```
  如果当前 key 已经存在，则设置当前 key 失败，返回 0
  ```

  - 解锁 del (key)

  ```
  得到锁的线程执行完任务，需要释放锁，以便其他线程可以进入,调用 del(key)
  ```

  - 配置锁超时 expire (key，30s）

  ```
  客户端奔溃或者网络中断，资源将会永远被锁住,即死锁，因此需要给key配置过期时间，以保证即使没有被显式释放，这把锁也要在一定时间后自动释放
  ```

  ```
  
  ```

  - 综合伪代码

  ```
  methodA(){
  ```

  ```
    String key = "coupon_66"
  ```

  ```
  
  ```

  ```
    if（setnx（key，1） == 1）{
  ```

  ```
        expire(key,30,TimeUnit.MILLISECONDS)
  ```

  ```
        try {
  ```

  ```
            //做对应的业务逻辑
  ```

  ```
            //查询用户是否已经领券
  ```

  ```
            //如果没有则扣减库存
  ```

  ```
            //新增领劵记录
  ```

  ```
        } finally {
  ```

  ```
            del（key）
  ```

  ```
        }
  ```

  ```
    }else{
  ```

  ```
  
  ```

  ```
      //睡眠100毫秒，然后自旋调用本方法
  ```

  ```
      methodA()
  ```

  ```
    }
  ```

  ```
  }
  ```

  - 存在哪些问题，大家自行思考下

   

   

   

   

#### 第3集 基于Redis实现分布式锁的几种坑你是否踩过《下》

**简介：手把手教你彻底掌握分布式锁+原生代码编写**

- 存在什么问题？

  - 多个命令之间不是原子性操作，如`setnx`和`expire`之间，如果`setnx`成功，但是`expire`失败，且宕机了，则这个资源就是死锁

  ```
  使用原子命令：设置和配置过期时间  setnx / setex
  ```

  ```
  如: set key 1 ex 30 nx
  ```

  ```
  java里面 redisTemplate.opsForValue().setIfAbsent("seckill_1","success",30,TimeUnit.MILLISECONDS)
  ```

  ![image-20210410165806304](https://file.xdclass.net/note/2021/redis/img/image-20210410165806304.png)

  - 业务超时，存在其他线程勿删，key 30秒过期，假如线程A执行很慢超过30秒，则key就被释放了，其他线程B就得到了锁，这个时候线程A执行完成，而B还没执行完成，结果就是线程A删除了线程B加的锁

  ```
  可以在 del 释放锁之前做一个判断，验证当前的锁是不是自己加的锁, 那 value 应该是存当前线程的标识或者uuid
  ```

  ```
  
  ```

  ```
  String key = "coupon_66"
  ```

  ```
  String value = Thread.currentThread().getId()
  ```

  ```
  
  ```

  ```
  if（setnx（key，value） == 1）{
  ```

  ```
      expire(key,30,TimeUnit.MILLISECONDS)
  ```

  ```
      try {
  ```

  ```
          //做对应的业务逻辑
  ```

  ```
      } finally {
  ```

  ```
        //删除锁，判断是否是当前线程加的
  ```

  ```
        if(get(key).equals(value)){
  ```

  ```
            //还存在时间间隔
  ```

  ```
            del（key）
  ```

  ```
          }
  ```

  ```
      }
  ```

  ```
  }else{
  ```

  ```
    
  ```

  ```
    //睡眠100毫秒，然后自旋调用本方法
  ```

  ```
  
  ```

  ```
  }
  ```

  - 进一步细化误删
    - 当线程A获取到正常值时，返回带代码中判断期间锁过期了，线程B刚好重新设置了新值，线程A那边有判断value是自己的标识，然后调用del方法，结果就是删除了新设置的线程B的值
    - 核心还是判断和删除命令 不是原子性操作导致
  - 总结
    - 加锁+配置过期时间：保证原子性操作
    - 解锁: 防止误删除、也要保证原子性操作

   

  - 那如何解决呢？下集讲解

 

 

 

 

 

 

 

 

 

 

#### 第4集 手把手教你彻底掌握分布式锁lua脚本+redis原生代码编写

**简介：手把手教你彻底掌握分布式锁+原生代码编写**

- 前面说了redis做分布式锁存在的问题

  - 核心是保证多个指令原子性，加锁使用setnx setex 可以保证原子性，那解锁使用 判断和删除怎么保证原子性
  - 文档：http://www.redis.cn/commands/set.html
  - 多个命令的原子性：采用 lua脚本+redis, 由于【判断和删除】是lua脚本执行，所以要么全成功，要么全失败

  ```
  //获取lock的值和传递的值一样，调用删除操作返回1，否则返回0
  ```

  ```
  
  ```

  ```
  String script = "if redis.call('get',KEYS[1]) == ARGV[1] then return redis.call('del',KEYS[1]) else return 0 end";
  ```

  ```
  
  ```

  ```
  //Arrays.asList(lockKey)是key列表，uuid是参数
  ```

  ```
  Integer result = redisTemplate.execute(new DefaultRedisScript<>(script, Integer.class), Arrays.asList(lockKey), uuid);
  ```

  - 全部代码

  ```
  /**
  ```

  ```
  * 原生分布式锁 开始
  ```

  ```
  * 1、原子加锁 设置过期时间，防止宕机死锁
  ```

  ```
  * 2、原子解锁：需要判断是不是自己的锁
  ```

  ```
  */
  ```

  ```
  @RestController
  ```

  ```
  @RequestMapping("/api/v1/coupon")
  ```

  ```
  public class CouponController {
  ```

  ```
  
  ```

  ```
      @Autowired
  ```

  ```
      private StringRedisTemplate redisTemplate;
  ```

  ```
  
  ```

  ```
  
  ```

  ```
      @GetMapping("add")
  ```

  ```
      public JsonData saveCoupon(@RequestParam(value = "coupon_id",required = true) int couponId){
  ```

  ```
  
  ```

  ```
          //防止其他线程误删
  ```

  ```
          String uuid = UUID.randomUUID().toString();
  ```

  ```
  
  ```

  ```
          String lockKey = "lock:coupon:"+couponId;
  ```

  ```
  
  ```

  ```
          lock(couponId,uuid,lockKey);
  ```

  ```
  
  ```

  ```
          return JsonData.buildSuccess();
  ```

  ```
  
  ```

  ```
      }
  ```

  ```
  
  ```

  ```
  
  ```

  ```
      private void lock(int couponId,String uuid,String lockKey){
  ```

  ```
  
  ```

  ```
  
  ```

  ```
          //lua脚本
  ```

  ```
          String script = "if redis.call('get',KEYS[1]) == ARGV[1] then return redis.call('del',KEYS[1]) else return 0 end";
  ```

  ```
  
  ```

  ```
          Boolean nativeLock = redisTemplate.opsForValue().setIfAbsent(lockKey,uuid,Duration.ofSeconds(30));
  ```

  ```
          System.out.println(uuid+"加锁状态:"+nativeLock);
  ```

  ```
          if(nativeLock){
  ```

  ```
              //加锁成功
  ```

  ```
  
  ```

  ```
              try{
  ```

  ```
                  //TODO 做相关业务逻辑
  ```

  ```
                  TimeUnit.SECONDS.sleep(10L);
  ```

  ```
  
  ```

  ```
              } catch (InterruptedException e) {
  ```

  ```
  
  ```

  ```
              } finally {
  ```

  ```
                  //解锁
  ```

  ```
                  Long result = redisTemplate.execute( new DefaultRedisScript<>(script,Long.class),Arrays.asList(lockKey),uuid);
  ```

  ```
                  System.out.println("解锁状态:"+result);
  ```

  ```
  
  ```

  ```
              }
  ```

  ```
  
  ```

  ```
          }else {
  ```

  ```
              //自旋操作
  ```

  ```
              try {
  ```

  ```
                  System.out.println("加锁失败，睡眠5秒 进行自旋");
  ```

  ```
                  TimeUnit.MILLISECONDS.sleep(5000);
  ```

  ```
              } catch (InterruptedException e) { }
  ```

  ```
  
  ```

  ```
              //睡眠一会再尝试获取锁
  ```

  ```
              lock(couponId,uuid,lockKey);
  ```

  ```
          }
  ```

  ```
      }
  ```

  ```
  
  ```

  ```
  
  ```

  ```
  }
  ```

  - 遗留一个问题，锁的过期时间，如何实现锁的自动续期 或者 避免业务执行时间过长，锁过期了？

    - 原生方式的话，一般把锁的过期时间设置久一点，比如10分钟时间

     

  - 原生代码+redis实现分布式锁使用比较复杂，且有些锁续期问题更难处理

    - 延伸出框架 官方推荐方式：https://redis.io/topics/distlock
    - 使用特别简单: 看看公司做的工业级项目代码

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第八章 分布缓存实战-List-Hash数据结构最佳案例实战

 

#### 第1集 在线教育-天热销视频榜单实战-List数据结构设计

**简介：在线教育-天热销视频榜单实战-List数据结构设计**

- 需求
  - 小滴课堂官网需要一个视频学习榜单，每天更新一次
  - 需要支持人工运营替换榜单位置
- 企业中流程
  - 定时任务计算昨天最多人学习的视频
  - 晚上12点到1点更新到榜单上
  - 预留一个接口，支持人工运营
- 类似场景
  - 京东：热销手机榜单、电脑榜单等
  - 百度：搜索热榜
- 疑惑：为啥不是实时计算，真正高并发下项目，都是预先计算好结果，然后直接返回数据，且存储结构最简单

![image-20210411192134001](https://file.xdclass.net/note/2021/redis/img/image-20210411192134001.png)

 

 

 

 

 

 

 

 

 

 

#### 第2集 在线教育-天热销视频榜单实战-编码最佳实践

**简介：在线教育-天热销视频榜单实战-编码最佳实践**

- 开发接口

```
    @RequestMapping("rank")
    public JsonData videoRank(){

        List<VideoDO> list = redisTemplate.opsForList().range(RANK_KEY,0,-1);
        return JsonData.buildSuccess(list);
    }
```

- 测试数据

```
@Test
  void saveRank(){

        String RANK_KEY = "rank:video";
        VideoDO video1 = new VideoDO(3,"PaaS工业级微服务大课","xdclass.net",1099);
        VideoDO video2 = new VideoDO(5,"AlibabaCloud全家桶实战","xdclass.net",59);
        VideoDO video3 = new VideoDO(53,"SpringBoot2.X+Vue3综合实战","xdclass.net",49);
        VideoDO video4 = new VideoDO(15,"玩转23种设计模式+最近实战","xdclass.net",49);
        VideoDO video5 = new VideoDO(45,"Nginx网关+LVS+KeepAlive","xdclass.net",89);
        redisTemplate.opsForList().leftPushAll(RANK_KEY,video4,video5,video3,video2,video1);

    }
```

- 人工运营操作榜单

```
    /**
     * 替换榜单第二名
     */
    @Test
    void replaceRank(){
        String RANK_KEY = "rank:video";
        VideoDO video = new VideoDO(42,"小滴课堂面试专题第一季高级工程师","xdclass.net",89);
        //在集合的指定位置插入元素,如果指定位置已有元素，则覆盖，没有则新增
        redisTemplate.opsForList().set(RANK_KEY,1,video);
    }
```

 

 

 

 

 

 

#### 第3集 自营电商平台-购物车实现案例-Hash数据结构最佳实践

**简介：自营电商平台-购物车实现案例-Hash数据结构最佳实践**

- 背景
  - 电商购物车实现，支持买多件商品，每个商品可以买不同数量
  - 支持高性能处理

![image-20210218224622798](https://file.xdclass.net/note/2021/redis/img/image-20210218224622798.png)

- 购物车常见实现方式

  - 实现方式一:存储到数据库
    - 性能存在瓶颈
  - 实现方式二:前端本地存储-localstorage-sessionstorage
    - localstorage在浏览器中存储 key/value 对，没有过期时间。
    - sessionstorage在浏览器中存储 key/value 对,在关闭会话窗口后将会删除这些数据。
  - 实现方式三:后端存储到缓存如redis
    - 可以开启AOF持久化防止重启丢失(推荐)

  

- 购物车数据结构介绍

  - 一个购物车里面，存在多个购物项
  - 所以 购物车结构是一个双层Map：
    - Map<String,Map<String,String>>
    - 第一层Map，Key是用户id
    - 第二层Map，Key是购物车中商品id，值是购物车数据

- 对应redis里面的存储

  - redis里面有多种数据结构，应该使用哪种？
  - 答案是 hash结构

  ![image-20210221210955210](https://file.xdclass.net/note/2021/redis/img/image-20210221210955210.png)

 

 

 

 

 

 

 

 

#### 第4集 高并发下的互联网电商购物车实战-相关VO类和数据准备

**简介：高并发下的互联网电商购物车实战-相关VO类和数据准备**

- VideoDO类
- CartItemVO

```
public class CartItemVO {

    /**
     * 商品id
     */
    private Integer productId;

    /**
     * 购买数量
     */
    private Integer buyNum;

    /**
     * 商品标题
     */
    private String productTitle;

    /**
     * 图片
     */
    private String productImg;

    /**
     * 商品单价
     */
    private int price ;

    /**
     * 总价格，单价+数量
     */
    private int totalPrice;


    public int getProductId() {
        return productId;
    }

    public void setProductId(int productId) {
        this.productId = productId;
    }

    public Integer getBuyNum() {
        return buyNum;
    }

    public void setBuyNum(Integer buyNum) {
        this.buyNum = buyNum;
    }

    public String getProductTitle() {
        return productTitle;
    }

    public void setProductTitle(String productTitle) {
        this.productTitle = productTitle;
    }

    public String getProductImg() {
        return productImg;
    }

    public void setProductImg(String productImg) {
        this.productImg = productImg;
    }

    /**
     * 商品单价 * 购买数量
     * @return
     */
    public int getTotalPrice() {

        return this.price*this.buyNum;
    }

    public int getPrice() {
        return price;
    }

    public void setPrice(int price) {
        this.price = price;
    }

    public void setTotalPrice(int totalPrice) {
        this.totalPrice = totalPrice;
    }
}
```

 

- CartIVO

```
public class CartVO {

    /**
     * 购物项
     */
    private List<CartItemVO> cartItems;


    /**
     * 购物车总价格
     */
    private Integer totalAmount;



    /**
     * 总价格
     * @return
     */
    public int getTotalAmount() {
        return cartItems.stream().mapToInt(CartItemVO::getTotalPrice).sum();
    }



    public List<CartItemVO> getCartItems() {
        return cartItems;
    }

    public void setCartItems(List<CartItemVO> cartItems) {
        this.cartItems = cartItems;
    }
}

```

 

- 数据源层

```
@Repository
public class VideoDao {

    private static Map<Integer,VideoDO> map = new HashMap<>();

    static {
        map.put(1,new VideoDO(1,"工业级PaaS云平台+SpringCloudAlibaba 综合项目实战(完结)","https://xdclass.net",1099));
        map.put(2,new VideoDO(2,"玩转新版高性能RabbitMQ容器化分布式集群实战","https://xdclass.net",79));
        map.put(3,new VideoDO(3,"新版后端提效神器MybatisPlus+SwaggerUI3.X+Lombok","https://xdclass.net",49));
        map.put(4,new VideoDO(4,"玩转Nginx分布式架构实战教程 零基础到高级","https://xdclass.net",49));
        map.put(5,new VideoDO(5,"ssm新版SpringBoot2.3/spring5/mybatis3","https://xdclass.net",49));
        map.put(6,new VideoDO(6,"新一代微服务全家桶AlibabaCloud+SpringCloud实战","https://xdclass.net",59));
    }


    /**
     * 模拟从数据库找
     * @param videoId
     * @return
     */
    public VideoDO findDetailById(int videoId) {
        return map.get(videoId);
    }
}

```

- json工具类

```
public class JsonUtil {

    // 定义jackson对象
    private static final ObjectMapper MAPPER = new ObjectMapper();

    /**
     * 将对象转换成json字符串。
     
     * @return
     */
    public static String objectToJson(Object data) {
        try {
            String string = MAPPER.writeValueAsString(data);
            return string;
        } catch (Exception e) {
            e.printStackTrace();
        }
        return null;
    }

    /**
     * 将json结果集转化为对象
     *
     * @param jsonData json数据
     * @param clazz 对象中的object类型
     * @return
     */
    public static <T> T jsonToPojo(String jsonData, Class<T> beanType) {
        try {
            T t = MAPPER.readValue(jsonData, beanType);
            return t;
        } catch (Exception e) {
            e.printStackTrace();
        }
        return null;
    }

}
```

 

 

 

 

 

 

 

 

#### 第5集 高并发下的互联网电商购物车实战-加入购物车接口开发

**简介：电商购物车实现案例-加入购物车接口开发**

- 添加购物车接口

```
    @RequestMapping("addCart")
    public JsonData addCart(int videoId,int buyNum){

        //获取购物车
        BoundHashOperations<String, Object, Object> myCart = getMyCartOps();

        Object cacheObj = myCart.get(videoId+"");
        String result = "";

        if (cacheObj != null) {
            result = (String) cacheObj;
        }
        if (cacheObj == null) {
            //不存在则新建一个购物项
            CartItemVO cartItem = new CartItemVO();
            //从数据库查询详情，我们这边直接随机写个

            VideoDO videoDO = videoDao.findDetailById(videoId);
            videoDO.setId(videoId);

            cartItem.setPrice(videoDO.getPrice());
            cartItem.setBuyNum(buyNum);
            cartItem.setProductId(videoId);
            cartItem.setProductImg(videoDO.getImg());
            cartItem.setProductTitle(videoDO.getTitle());
            myCart.put(videoId+"", JsonUtil.objectToJson(cartItem));

        } else {

            //存在则新增数量
            CartItemVO cartItem = JsonUtil.jsonToPojo(result, CartItemVO.class);
            cartItem.setBuyNum(cartItem.getBuyNum() + buyNum);
            myCart.put(videoId+"", JsonUtil.objectToJson(cartItem));

        }

        return JsonData.buildSuccess();

    }
```

- 购物车方法抽取

```
   /**
     * 抽取我的购物车通用方法
     *
     * @return
     */
    private BoundHashOperations<String, Object, Object> getMyCartOps() {
        String cartKey = getCartKey();
        return redisTemplate.boundHashOps(cartKey);
    }


    /**
     * 获取购物车的key
     *
     * @return
     */
    private String getCartKey() {
        //从拦截器获取 ，这里写死即可，每个用户不一样
        int userId = 88;
        String cartKey = String.format("product:cart:%s", userId);
        return cartKey;
    }
```

 

 

 

 

 

 

 

 

#### 第6集 高并发下的互联网电商购物车实战-查看和清空购物车功能开发

**简介：高并发下的互联网电商购物车实战-查看和清空购物车功能开发**

- 查看我的购物车

```
 @GetMapping("/mycart")
    public JsonData findMyCart(){

        BoundHashOperations<String,Object,Object> myCart = getMyCartOps();

        List<Object> itemList = myCart.values();

        List<CartItemVO> cartItemVOList = new ArrayList<>();

        for(Object item: itemList){
            CartItemVO cartItemVO = JsonUtil.jsonToPojo((String)item,CartItemVO.class);
            cartItemVOList.add(cartItemVO);
        }

        //封装成cartvo
        CartVO cartVO = new CartVO();
        cartVO.setCartItems(cartItemVOList);


        return JsonData.buildSuccess(cartVO);
    }

```

- 清空购物车

```
 @GetMapping("/clear")
public JsonData clear() {
        String cartKey = getCartKey();
        redisTemplate.delete(cartKey);
         return JsonData.buildSuccess();
}
```

 

 

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第九章 分布缓存实战-Set集合数据结构最佳案例实战

 

#### 第1集 案例实战之大数据下的用户画像标签去重

**简介：案例实战需求之大数据下的用户画像标签去重**

- 介绍
  - 用户画像 英文为User Profile，是根据用户基本属性、社会属性、行为属性、心理属性等真实信息而抽象出的一个标签化的、虚拟的用户模型。“用户画像”的实质是对 “人”的数字化。
  - 应用场景有很多，比如个性化推荐、精准营销、金融风控、精细化运营等等， 举个例子来理解用户画像的实际应用价值，我们经常用手机网购，淘宝里面的千人千面
  - 通过“标签 tag”来对用户的多维度特征进行提炼和标识，那每个人的用户画像就需要存储，set集合就适合去重
  - 用户画像不止针对某个人，也可以某一人群或行业的画像
  - 利用redis可以很好的去重
- 案例

```
       BoundSetOperations operations  = redisTemplate.boundSetOps("user:tags:1");

        operations.add("car","student","rich","guangdong","dog","rich");

        Set<String> set1 = operations.members();

        System.out.println(set1);

        operations.remove("dog");

        Set<String> set2 = operations.members();
        System.out.println(set2);

        return JsonData.buildSuccess();
```

 

 

 

 

 

 

 

 

 

 

 

#### 第2集 案例实战社交应用里面之关注、粉丝、共同好友案例

**简介：案例实战社交应用里面之关注、粉丝、共同好友案例**

- 背景
  - 社交应用里面的知识，关注、粉丝、共同好友案例
- 案例实战

![image-20210413134244293](https://file.xdclass.net/note/2021/redis/img/image-20210413134244293.png)

 

- 代码

```
    public void testSet(){

        BoundSetOperations operationLW  = redisTemplate.boundSetOps("user:lw");

        operationLW.add("A","B","C","D","E");
        System.out.println("老王的粉丝:"+operationLW.members());
        BoundSetOperations operationXD  = redisTemplate.boundSetOps("user:xd");

        operationXD.add("A","B","F","G","H","J");
        System.out.println("小D的粉丝:"+operationXD.members());

        //差集
        Set lwSet = operationLW.diff("user:xd");
        System.out.println("老王的优势:"+lwSet);

        //差集
        Set xdSet = operationXD.diff("user:lw");
        System.out.println("小滴的优势:"+xdSet);

        //交集
        Set interSet =  operationLW.intersect("user:xd");
        System.out.println("共同好友:"+interSet);

        //并集
        Set unionSet = operationLW.union("user:xd");
        System.out.println("两个人的并集:"+unionSet);
    
      //用户A是否是 老王 的粉丝
        boolean flag = operationLW.isMember("A");
        System.out.println(flag);
    }
```

 

 

 

 

 

 

 

#### 第3集 案例实战之SortedSet开发用户积分实时榜单最佳实践

**简介：案例实战之SortedSet用户积分实时榜单最佳实践**

- 背景
  - 用户玩游戏-积分实时榜单
  - IT视频热销实时榜单
  - 电商商品热销实时榜单
  - 一般的排行榜读多写少，可以对 master 进行写入操作，然后多个 slave 进行读取操作。
  - 如果是对象记得重写HashCode与Equals方法
- 对象准备

```
public class UserPointVO {

    public UserPointVO(String username, String phone) {
        this.username = username;
        this.phone = phone;
    }

    private String username;

    private String phone;


}

```

 

```
@Test
  void testData() {

        UserPoint p1 = new UserPoint("老王","13113");
        UserPoint p2 = new UserPoint("老A","324");
        UserPoint p3 = new UserPoint("老B","242");
        UserPoint p4 = new UserPoint("老C","542345");
        UserPoint p5 = new UserPoint("老D","235");
        UserPoint p6 = new UserPoint("老E","1245");
        UserPoint p7 = new UserPoint("老F","2356432");
        UserPoint p8 = new UserPoint("老G","532332");

        BoundZSetOperations<String, UserPoint> operations = redisTemplate.boundZSetOps("point:rank:real");


        operations.add(p1,888);
        ...
        

  }
```

 

- 接口开发
  - 返回榜单-从大到小排序
  - 查看这个人的排名,从大到小，0就是第一
  - 给某个用户加积分
  - 查看某个用户的积分

 

 

 

 

#### 第4集 案例实战之SortedSet开发用户积分实时榜单多接口实战

**简介：案例实战之SortedSet用户积分实时榜单多接口实战**

- 多接口实战
  - 接口开发
    - 返回榜单-从大到小排序
    - 查看这个人的排名,从大到小，0就是第一
    - 给某个用户加积分
    - 查看某个用户的积分

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十章 新版SpringBoot2.X+MybatisPlus+SpringCache框架项目实战

 

#### 第1集 项目缓存提效神器-SpringCache缓存框架介绍

**简介：SpringCache缓存框架介绍**

- SpringCache简介

  - 文档：https://spring.io/guides/gs/caching/
  - 自Spring 3.1起，提供了类似于@Transactional注解事务的注解Cache支持，且提供了Cache抽象
  - 提供基本的Cache抽象，方便切换各种底层Cache
  - 只需要更少的代码就可以完成业务数据的缓存
  - 提供事务回滚时也自动回滚缓存，支持比较复杂的缓存逻辑
  - 核心
    - 一个是Cache接口，缓存操作的API；
    - 一个是CacheManager管理各类缓存，有多个缓存框架的实现

- 讲课方式

  - 很多其他地方的教程，使用单元测试的方式教SpringCache使用
  - 多个同学反馈看了也不懂在SpringBoot或者Cloud微服务项目中使用
  - 本章内容采用案例实战的方式，教大家怎么使用，工作中开发项目直接采用即可
  - 学会触类旁通，举一反三

- 使用

  - 项目中引入starter

  ```
  <dependency>
  ```

  ```
             <groupId>org.springframework.boot</groupId>
  ```

  ```
             <artifactId>spring-boot-starter-cache</artifactId>
  ```

  ```
  </dependency>
  ```

  - 配置文件指定缓存类型

  ```
  spring:
  ```

  ```
    cache:
  ```

  ```
      type: redis
  ```

  - 启动类开启缓存注解

  ```
  @EnableCaching
  ```

 

 

 

 

 

 

 

 

 

 

 

#### 第2集 SpringBoot2.x整合MybatisPlus连接Mysql数据库

**简介：整合MybatisPlus连接Mysql数据库**

- 备注：
  - 如果不会MybatisPlus的同学，联系客服，可以5折购买视频【参加我们Redis6实战的同学采有】
  - 链接：https://detail.tmall.com/item.htm?id=635500972913
- 添加依赖

```
 <!--mybatis plus和springboot整合-->
     <dependency>
                <groupId>com.baomidou</groupId>
                <artifactId>mybatis-plus-boot-starter</artifactId>
                <version>3.4.0</version>
      </dependency>

<!--数据库驱动-->           
    <dependency>
      <groupId>mysql</groupId>
      <artifactId>mysql-connector-java</artifactId>
      <version>8.0.15</version>
    </dependency>

```

- 新增配置

```
#==============================数据库相关配置========================================
#数据库配置
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://127.0.0.1:3306/xdclass_user?useUnicode=true&characterEncoding=utf-8&useSSL=false&serverTimezone=Asia/Shanghai
    username: root
    password: xdclass.net

#配置plus打印sql日志
mybatis-plus:
  configuration:
    log-impl: org.apache.ibatis.logging.stdout.StdOutImpl
```

- 数据库和表建立

```
CREATE TABLE `product` (
  `id` int(11) unsigned NOT NULL AUTO_INCREMENT,
  `title` varchar(128) DEFAULT NULL COMMENT '标题',
  `cover_img` varchar(128) DEFAULT NULL COMMENT '封面图',
  `detail` varchar(256) DEFAULT '' COMMENT '详情',
  `amount` int(10) DEFAULT NULL COMMENT '新价格',
  `stock` int(11) DEFAULT NULL COMMENT '库存',
  `create_time` datetime DEFAULT NULL COMMENT '创建时间',
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=5 DEFAULT CHARSET=utf8mb4;

```

- 插入数据

```
INSERT INTO `product` (`id`, `title`, `cover_img`, `detail`, `amount`, `stock`, `create_time`)
VALUES
  (1, '老王-小滴课堂抱枕', 'https://file.xdclass.net/video/2020/alibabacloud/zt-alibabacloud.png', 'https://file.xdclass.net/video/2021/60-MLS/summary.jpeg', 213, 100, '2021-09-12 00:00:00'),
  (2, '老王-技术人的杯子Linux', 'https://file.xdclass.net/video/2020/alibabacloud/zt-alibabacloud.png', 'https://file.xdclass.net/video/2021/59-Postman/summary.jpeg', 42, 100, '2021-03-12 00:00:00'),
  (3, '技术人的杯子docker', 'https://file.xdclass.net/video/2020/alibabacloud/zt-alibabacloud.png', 'https://file.xdclass.net/video/2021/60-MLS/summary.jpeg', 12, 20, '2022-09-22 00:00:00'),
  (4, '技术人的杯子git', 'https://file.xdclass.net/video/2020/alibabacloud/zt-alibabacloud.png', 'https://file.xdclass.net/video/2021/60-MLS/summary.jpeg', 14, 20, '2022-11-12 00:00:00');

```

- DO类编写

```
@TableName("product")
public class ProductDO  {

    @TableId(value = "id", type = IdType.AUTO)
    private Long id;

    /**
     * 标题
     */
    private String title;

    /**
     * 封面图
     */
    private String coverImg;

    /**
     * 详情
     */
    private String detail;

    /**
     * 新价格
     */
    private Integer amount;

    /**
     * 库存
     */
    private Integer stock;

    /**
     * 创建时间
     */
    private Date createTime;

}
```

 

 

 

 

 

 

 

 

 

 

#### 第3集 SpringBoot+MybatisPlus开发商品的CRUD接口

**简介： SpringBoot+MybatisPlus开发商品列表的CRUD接口**

- 编写Mapper

```
public interface ProductMapper extends BaseMapper<ProductDO> {
}
```

- 编写Service

```

    @Override
    public int save(ProductDO productDO) {
        return productMapper.insert(productDO);
    }

    @Override
    public int delById(int id) {
        return productMapper.deleteById(id);
    }

    @Override
    public int updateById(ProductDO productDO) {
        return productMapper.updateById(productDO);
    }

    @Override
    public ProductDO findById(int id) {
        return productMapper.selectById(id);
    }

```

 

- 编写controller

 

 

 

 

 

 

 

 

#### 第4集 SpringBoot+MybatisPlus开发商品分页接口

**简介： SpringBoot+MybatisPlus开发商品分页接口**

- 为啥要开发分页接口？
  - 很多同学不知道分页怎么缓存
- MybatisPlus分页接口

```
  @Override
    public Map<String, Object> page(int page, int size) {

        Page<ProductDO> pageInfo = new Page<>(page, size);

        IPage<ProductDO> productDOIPage = productMapper.selectPage(pageInfo, null);

        Map<String, Object> pageMap = new HashMap<>(3);

        pageMap.put("total_record", productDOIPage.getTotal());
        pageMap.put("total_page", productDOIPage.getPages());
        pageMap.put("current_data", productDOIPage.getRecords());

        return pageMap;
    }
```

- controller编写

 

 

 

- 分页插件配置

```
    /**
     * 新的分页插件
     */
    @Bean
    public MybatisPlusInterceptor mybatisPlusInterceptor() {
        MybatisPlusInterceptor interceptor = new MybatisPlusInterceptor();
        interceptor.addInnerInterceptor(new PaginationInnerInterceptor(DbType.MYSQL));
        return interceptor;
    }
```

 

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十一章 SpringCache常用注解介绍+框架案例实战

 

#### 第1集 SpringCache框架常用之Cacheable实战

**简介：SpringCache框架常用注解Cacheable**

- Cacheable注解
  - 标记在一个方法上，也可以标记在一个类上
  - 缓存标注对象的返回结果，标注在方法上缓存该方法的返回值，标注在类上缓存该类所有的方法返回值
  - value 缓存名称，可以有多个
  - key 缓存的key规则，可以用springEL表达式，默认是方法参数组合
  - condition 缓存条件，使用springEL编写，返回true才缓存

- 案例

```
//对象
@Cacheable(value = {"product"}, key="#root.methodName")

//分页
@Cacheable(value = {"product_page"},key="#root.methodName + #page+'_'+#size")
```

- spEL表达式
  - methodName 当前被调用的方法名
    - root.methodname
  - args 当前被调用的方法的参数列表
    - root.args[0]
  - result 方法执行后的返回值
    - result

 

 

#### 第2集 SpringCache框架自定义CacheManager配置和过期时间

**简介：SpringCache框架自定义CacheManager配置和过期时间**

- 修改redis缓存序列化器和配置manager过期时间

```
    
    @Bean
    @Primary
    public RedisCacheManager cacheManager1Hour(RedisConnectionFactory connectionFactory) {
        RedisCacheConfiguration config = instanceConfig(3600L);
        return RedisCacheManager.builder(connectionFactory)
                .cacheDefaults(config)
                .transactionAware()
                .build();
    }

    @Bean
    public RedisCacheManager cacheManager1Day(RedisConnectionFactory connectionFactory) {

        RedisCacheConfiguration config = instanceConfig(3600 * 24L);
        return RedisCacheManager.builder(connectionFactory)
                .cacheDefaults(config)
                .transactionAware()
                .build();
    }

    private RedisCacheConfiguration instanceConfig(Long ttl) {

        Jackson2JsonRedisSerializer<Object> jackson2JsonRedisSerializer = new Jackson2JsonRedisSerializer<>(Object.class);
        ObjectMapper objectMapper = new ObjectMapper();
        objectMapper.disable(SerializationFeature.WRITE_DATES_AS_TIMESTAMPS);
        objectMapper.registerModule(new JavaTimeModule());
        // 去掉各种@JsonSerialize注解的解析
        objectMapper.configure(MapperFeature.USE_ANNOTATIONS, false);
        // 只针对非空的值进行序列化
        objectMapper.setSerializationInclusion(JsonInclude.Include.NON_NULL);
        // 将类型序列化到属性json字符串中
        objectMapper.activateDefaultTyping(LaissezFaireSubTypeValidator.instance ,
                ObjectMapper.DefaultTyping.NON_FINAL, JsonTypeInfo.As.PROPERTY);

        jackson2JsonRedisSerializer.setObjectMapper(objectMapper);

        return RedisCacheConfiguration.defaultCacheConfig()
                .entryTtl(Duration.ofSeconds(ttl))
                .disableCachingNullValues()
                .serializeValuesWith(RedisSerializationContext.SerializationPair.fromSerializer(jackson2JsonRedisSerializer));

    }
```

 

 

 

 

 

 

 

#### 第3集 SpringCache框架自定义缓存KeyGenerator

**简介：SpringCache框架自定义缓存KeyGenerator**

- Key规则定义麻烦，支持自定规则
- 实战

```
    @Bean
    public KeyGenerator springCacheDefaultKeyGenerator(){

        return new KeyGenerator() {
            @Override
            public Object generate(Object o, Method method, Object... objects) {
                return o.getClass().getSimpleName() + "_"
                        + method.getName() + "_"
                        + StringUtils.arrayToDelimitedString(objects, "_");
            }
        };

    }
```

- 使用
  - key 属性和keyGenerator属性只能二选一

```
@Cacheable(value = {"product"},keyGenerator = "springCacheCustomKeyGenerator", cacheManager = "cacheManager1Minute")

```

 

 

 

 

 

 

 

 

 

#### 第4集 SpringCache框架常用之CachePut实战

**简介：SpringCache框架常用注解CachePut**

- CachePut
  - 根据方法的请求参数对其结果进行缓存，每次都会触发真实方法的调用
  - value 缓存名称，可以有多个
  - key 缓存的key规则，可以用springEL表达式，默认是方法参数组合
  - condition 缓存条件，使用springEL编写，返回true才缓存
- 案例实战

```
@CachePut(value = {"product"},key = "#productDO.id")
```

 

 

 

 

 

 

 

 

 

 

#### 第5集 SpringCache框架常用之CacheEvict实战

**简介：SpringCache框架常用注解CacheEvict**

- CacheEvict
  - 从缓存中移除相应数据, 触发缓存删除的操作
  - value 缓存名称，可以有多个
  - key 缓存的key规则，可以用springEL表达式，默认是方法参数组合
  - beforeInvocation = false
    - 缓存的清除是否在方法之前执行 ,默认代表缓存清除操作是在方法执行之后执行;
    - 如果出现异常缓存就不会清除
  - beforeInvocation = true
    - 代表清除缓存操作是在方法运行之前执行，无论方法是否出现异常，缓存都清除
- 案例实战

```
@CacheEvict(value = {"product"},key = "#root.args[0]")
```

 

 

 

 

 

 

 

 

 

 

 

#### 第6集 SpringCache框架常用之多注解组合Caching实战

**简介：SpringCache框架多注解组合Caching**

- Caching
  - 组合多个Cache注解使用
  - 允许在同一方法上使用多个嵌套的@Cacheable、@CachePut和@CacheEvict注释
- 实战

```
  @Caching(
            cacheable = {
                    @Cacheable(value = "product",keyGenerator = "xdclassKeyGenerator")
            },
            put = {
                    @CachePut(value = "product",key = "#id"),
                    @CachePut(value = "product",key = "'stock:'+#id")
            }
    )
```

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十二章 分布式缓存面试题+SpringCache解决方案

 

#### 第1集 【面试题】分布式缓存必考题之缓存击穿+解决方案

**简介：分布式缓存必考题之缓存击穿+解决方案**

- 缓存击穿 (某个热点key缓存失效了)
  - 缓存中没有但数据库中有的数据，假如是热点数据，那key在缓存过期的一刻，同时有大量的请求，这些请求都会击穿到DB，造成瞬时DB请求量大、压力增大。
  - 和缓存雪崩的区别在于这里针对某一key缓存，后者则是很多key。

- 预防
  - 设置热点数据不过期
  - 定时任务定时更新缓存
  - 设置互斥锁

- SpringCache解决方案
  - 缓存的同步 sync
  - sync 可以指示底层将缓存锁住，使只有一个线程可以进入计算，而其他线程堵塞，直到返回结果更新到缓存中

```
@Cacheable(value = {"product"},key = "#root.args[0]", cacheManager = "customCacheManager", sync=true)
```

 

 

 

 

#### 第2集 【面试题】分布式缓存必考题之缓存雪崩+解决方案

**简介：分布式缓存必考题之缓存雪崩+解决方案**

- 缓存雪崩 (多个热点key都过期)

  - 大量的key设置了相同的过期时间，导致在缓存在同一时刻全部失效，造成瞬时DB请求量大、压力骤增，引起雪崩

  - 预防

    - 存数据的过期时间设置随机，防止同一时间大量数据过期现象发生
    - 设置热点数据永远不过期，定时任务定时更新

  - SpringCache解决方案

    - 设置差别的过时时间
    - 比如CacheManager配置多个过期时间维度
    - 配置文件 time-to-live 配置

    ```
     cache:
    ```

    ```
       #使用的缓存类型
    ```

    ```
        type: redis
    ```

    ```
       #过时时间
    ```

    ```
        redis:
    ```

    ```
          time-to-live: 3600000
    ```

    ```
          # 开启前缀，默以为true
    ```

    ```
          use-key-prefix: true
    ```

    ```
          # 键的前缀,默认就是缓存名cacheNames
    ```

    ```
          key-prefix: XD_CACHE
    ```

    ```
          # 是否缓存空结果，防止缓存穿透，默以为true
    ```

    ```
          cache-null-values: true
    ```

     

 

 

 

 

 

#### 第3集 【面试题】分布式缓存必考题之缓存穿透+解决方案

**简介：分布式缓存必考题之缓存穿透+解决方案**

- 缓存穿透（查询不存在数据）

  - 查询一个不存在的数据，由于缓存是不命中的，并且出于容错考虑，如发起为id为“-1”不存在的数据

  - 如果从存储层查不到数据则不写入缓存这将导致这个不存在的数据每次请求都要到存储层去查询，失去了缓存的意义。存在大量查询不存在的数据，可能DB就挂掉了，这也是黑客利用不存在的key频繁攻击应用的一种方式。

  - 预防

    - 接口层增加校验，数据合理性校验
    - 缓存取不到的数据，在数据库中也没有取到，这时也可以将key-value对写为key-null，设置短点的过期时间，防止同个key被一直攻击

  - SpringCache解决方案

    - 空结果也缓存，默认不配置condition或者unless就行

    ```
     cache:
    ```

    ```
       #使用的缓存类型
    ```

    ```
        type: redis
    ```

    ```
       #过时时间
    ```

    ```
        redis:
    ```

    ```
          time-to-live: 3600000
    ```

    ```
          # 开启前缀，默以为true
    ```

    ```
          use-key-prefix: true
    ```

    ```
          # 键的前缀,默认就是缓存名cacheNames
    ```

    ```
          key-prefix: XD_CACHE
    ```

    ```
          # 是否缓存空结果，防止缓存穿透，默以为true
    ```

    ```
          cache-null-values: true
    ```

     

 

 

 

#### 第4集 SpringCache整合SpringBoot案例总结

**简介：SpringCache整合SpringBoot案例总结**

- 学会触类旁通，举一反三
- 企业中使用也是这样用的，根据项目和团队开发规范简单调整
- 给大家看一个案例代理：大课项目训练营中使用
  - 工业级PaaS云平台+SpringCloudAlibaba 综合项目实战
  - 学习地址：https://detail.tmall.com/item.htm?id=634842400121&skuId=4611246228920
  - 基于2核4g，阿里云ECS通用性服务器
    - 使用缓存前，单机qps 是4千
    - 使用分布式缓存3万
    - 使用分布式缓存+本地缓存 5万 单机
    - 高并发下-容器编排自动化扩容，只要有足够的服务器，可以无限扩容
    - 阿里、腾讯、百度、京东、美团、字节等，都是这样的流程, 应对海量请求

![image-20210415131115251](https://file.xdclass.net/note/2021/redis/img/image-20210415131115251.png)

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十三章 【高级篇】分布式缓存Redis6.x持久化配置实战-AOF和RDB

 

#### 第1集 Redis6.x持久化介绍和RDB讲解

**简介： Redis6.x持久化配置介绍和RDB讲解**

- Redis持久化介绍
  - Redis是一个内存数据库，如果没有配置持久化，redis重启后数据就全丢失
  - 因此开启redis的持久化功能，将数据保存到磁盘上，当redis重启后，可以从磁盘中恢复数据。
- 两种持久化方式
  - RDB (Redis DataBase)
  - AOF (append only file）
- RDB持久化介绍
  - 在指定的时间间隔内将内存中的数据集快照写入磁盘
  - 默认的文件名为dump.rdb
  - 产生快照的情况
    - save
      - 会阻塞当前Redis服务器，执行save命令期间，Redis不能处理其他命令，直到RDB过程完成为止
    - bgsave
      - fork创建子进程，RDB持久化过程由子进程负责，会在后台异步进行快照操作，快照同时还可以响应客户端请求
    - 自动化
      - 配置文件来完成，配置触发 Redis的 RDB 持久化条件
      - 比如 "save m n"。表示m秒内数据集存在n次修改时，自动触发bgsave
    - 主从架构
      - 从服务器同步数据的时候，会发送sync执行同步操作，master主服务器就会执行bgsave
- 优点
  - RDB文件紧凑，全量备份，适合用于进行备份和灾难恢复
  - 在恢复大数据集时的速度比 AOF 的恢复速度要快
  - 生成的是一个紧凑压缩的二进制文件
- 缺点
  - 每次快照是一次全量备份，fork子进程进行后台操作，子进程存在开销
  - 在快照持久化期间修改的数据不会被保存，可能丢失数据

 

- 核心配置
  - dir 持久化文件的路径
  - dbfilename 文件名

```

#任何ip可以访问
bind 0.0.0.0

#守护进程
daemonize yes

#密码
requirepass 123456

#日志文件
logfile "/usr/local/redis/log/redis.log"

#持久化文件名称
dbfilename xdclass.rdb

#持久化文件存储路径
dir /usr/local/redis/data

#持久化策略, 10秒内有个1个key改动，执行快照
save 10 1

######之前配置######

#导出rdb数据库文件压缩字符串和对象,默认是yes，会浪费CPU但是节省空间
rdbcompression yes
# 导入时是否检查
rdbchecksum yes
```

 

 

 

 

 

 

 

 

 

#### 第2集 分布式缓存Redis6.x持久化配置RDB操作实战

**简介： 分布式缓存Redis6.x持久化配置RDB操作实战**

- 配置持久化
  - dir 持久化文件的路径
  - dbfilename 文件名
- save
- bgsave
- 配置文件触发

```
bind 0.0.0.0

daemonize yes

requirepass 123456Xdclass

logfile "/usr/local/redis/log/redis.log"

dbfilename xdclass.rdb

dir /usr/local/redis/data

#关闭rdb
#save ""

#10秒2个key变动则触发rdb
save 10 2
#100秒5个key变动则触发rdb
save 100 5

#压缩
rdbcompression yes
#检查
rdbchecksum yes
```

 

 

- 备注: linux内存分配策略

```
0 表示内核将检查是否有足够的可用内存供应用进程使用；如果有足够的可用内存，内存申请允许；否则，内存申请失败，并把错误返回给应用进程

1 表示内核允许分配所有的物理内存，而不管当前的内存状态如何。
2 表示内核允许分配超过所有物理内存和交换空间总和的内存

解决方式
echo 1 > /proc/sys/vm/overcommit_memory


持久化配置
vim /etc/sysctl.conf

改为
vm.overcommit_memory=1
修改sysctl.conf后，需要执行 sysctl -p 以使生效。
```

![image-20210416105154918](https://file.xdclass.net/note/2021/redis/img/image-20210416105154918.png)

 

 

 

 

 

 

 

 

 

#### 第3集 Redis6.x持久化配置AOF介绍和配置实战

**简介： Redis6.x持久化配置AOF介绍和配置实战**

- AOF持久化介绍
  - append only file，追加文件的方式，文件容易被人读懂
  - 以独立日志的方式记录每次写命令， 重启时再重新执行AOF文件中的命令达到恢复数据的目的
  - 写入过程宕机，也不影响之前的数据，可以通过 redis-check-aof检查修复问题

 

- 配置实战

  - appendonly yes，默认不开启
  - AOF文件名 通过 appendfilename 配置设置，默认文件名是appendonly.aof
  - 存储路径同 RDB持久化方式一致，使用dir配置

   

- 核心原理

  - Redis每次写入命令会追加到aof_buf（缓冲区）
  - AOF缓冲区根据对应的策略向硬盘做同步操作
  - 高频AOF会带来影响，特别是每次刷盘

   

- 提供了3种同步方式，在性能和安全性方面做出平衡

  - appendfsync always
    - 每次有数据修改发生时都会写入AOF文件，消耗性能多
  - appendfsync everysec
    - 每秒钟同步一次，该策略为AOF的缺省策略。
  - appendfsync no
    - 不主从同步，由操作系统自动调度刷磁盘，性能是最好的，但是最不安全

```
bind 0.0.0.0

daemonize yes

requirepass 123456Xdclass

logfile "/usr/local/redis/log/redis.log"

dbfilename xdclass.rdb

dir /usr/local/redis/data

#save 10 2
#save 100 5
save ""
rdbcompression yes
#对rdb数据进行校验，耗费CPU资源，默认为yes
rdbchecksum yes

appendonly yes
appendfilename "appendonly.aof"
appendfsync everysec
```

 

 

 

 

 

 

 

 

 

 

#### 第4集 Redis6.x持久化配置AOF重新rewrite配置实战

**简介： Redis6.x持久化配置AOF重新rewrite配置实战**

- rewrite 重写介绍
  - AOF文件越来越大，需要定期对AOF文件进行重写达到压缩
  - 旧的AOF文件含有无效命令会被忽略，保留最新的数据命令
  - 多条写命令可以合并为一个
  - AOF重写降低了文件占用空间
  - 更小的AOF 文件可以更快地被Redis加载

 

- 重写触发配置
  - 手动触发
    - 直接调用bgrewriteaof命令
  - 自动触发
    - auto-aof-rewrite-min-size和auto-aof-rewrite-percentage参数
    - auto-aof-rewrite-min-size
      - 表示运行AOF重写时文件最小体积，默认 为64MB。
    - auto-aof-rewrite-percentage
      - 代表当前AOF文件空间和上一次重写后AOF文件空间（aof_base_size）的比值。
- 常用配置

```
# 是否开启aof
appendonly yes

# 文件名称
appendfilename "appendonly.aof"

# 同步方式
appendfsync everysec

# aof重写期间是否同步
no-appendfsync-on-rewrite no

# 重写触发配置
auto-aof-rewrite-percentage 100
auto-aof-rewrite-min-size 64mb

# 加载aof时如果有错如何处理
# yes表示如果aof尾部文件出问题，写log记录并继续执行。no表示提示写入等待修复后写入

aof-load-truncated yes 
```

 

 

 

 

 

 

 

 

 

#### 第5集 Redis6.x持久化配置AOF+RDB的选择问题和混合模式

**简介： Redis6.x持久化配置AOF和RDB的选择问题**

- Redis提供了不同的持久性选项：
  - RDB持久化以指定的时间间隔执行数据集的时间点快照。
  - AOF持久化记录服务器接收的每个写入操作，将在服务器启动时再次读取，重建原始数据集。使用与Redis协议本身相同的格式以仅追加方式记录命令，当文件太大时，Redis能够重写

- 补充之前的配置

```
auto-aof-rewrite-min-size
AOF文件最小重写大小，只有当AOF文件大小大于该值时候才可能重写,6.x默认配置64mb。

auto-aof-rewrite-percentage
当前AOF文件大小和最后一次重写后的大小之间的比率等于或者等于指定的增长百分比，如100代表当前AOF文件是上次重写的两倍时候才重写。　
```

 

- RDB的优缺点
  - 优点：
    - RDB最大限度地提高了Redis的性能，父进程不需要参与磁盘I/O
    - RDB文件紧凑，全量备份，适合用于进行备份和灾难恢复
    - 在恢复大数据集时的速度比 AOF 的恢复速度要快
    - 生成的是一个紧凑压缩的二进制文件
  - 缺点：
    - 如果您需要在Redis停止工作时（例如断电后）将数据丢失的可能性降至最低，则RDB并不好
    - RDB经常需要fork才能使用子进程持久存储在磁盘上。如果数据集很大，Fork可能会非常耗时
- AOF的优缺点
  - 优点：
    - 数据更加安全
    - 当Redis AOF文件太大时，Redis能够在后台自动重写AOF
    - AOF以易于理解和解析的格式，一个接一个地包含所有操作的日志
  - 缺点：
    - AOF文件通常比同一数据集的等效RDB文件大
    - 根据确切的fsync策略，恢复的时候AOF可能比RDB慢

- 在线上我们到底该怎么做？
  - RDB持久化与AOF持久化一起使用
  - 如果Redis中的数据并不是特别敏感或者可以通过其它方式重写生成数据
  - 集群中可以关闭AOF持久化，靠集群的备份方式保证可用性
  - 自己制定策略定期检查Redis的情况，然后可以手动触发备份、重写数据；
  - 采用集群和主从同步

 

- Redis4.0后开始的rewrite支持**混合模式**
  - 就是rdb和aof一起用
  - 直接将rdb持久化的方式来操作将二进制内容覆盖到aof文件中,rdb是二进制，所以很小
  - 有写入的话还是继续append追加到文件原始命令，等下次文件过大的时候再次rewrite
  - 默认是开启状态
  - 好处
    - 混合持久化结合了RDB持久化 和 AOF 持久化的优点,采取了rdb的文件小易于灾难恢复
    - 同时结合AOF，增量的数据以AOF方式保存了，数据更少的丢失
  - 坏处
    - 前部分是RDB格式，是二进制，所以阅读性较差
  - 数据恢复
    - 先看是否存在aof文件，若存在则先按照aof文件恢复，aof比rdb全，且aof文件也rewrite成rdb二进制格式
    - 若aof不存在，则才会查找rdb是否存在

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十四章 【高级篇】Redis6.X服务端info+config实战和key淘汰算法

 

#### 第1集 Redis6.x服务端配置 info命令介绍-生产监控知识

**简介： Redis6.x服务端配置info命令介绍**

- info命令介绍

  - 服务器的各种信息和统计数值

  ```
  Server：有关redis服务器的常规信息
  ```

  ```
    redis_mode:standalone                         # 运行模式，单机或者集群
  ```

  ```
    multiplexing_api:epoll                        # redis所使用的事件处理机制
  ```

  ```
    run_id:3abd26c33dfd059e87a0279defc4c96c13962ede # redis服务器的随机标识符(用于sentinel和集群)
  ```

  ```
    config_file:/usr/local/redis/conf/redis.conf       # 配置文件路径
  ```

  ```
  
  ```

  ```
  Clients：客户端连接部分
  ```

  ```
    connected_clients:10           # 已连接客户端的数量(不包括通过slave连接的客户端)
  ```

  ```
    
  ```

  ```
  Memory：内存消耗相关信息
  ```

  ```
    used_memory:874152  # 使用内存，以字节（byte）B为单位
  ```

  ```
    used_memory_human:853.66K # 以人类可读的格式返回 Redis 分配的内存总量
  ```

  ```
    used_memory_rss:2834432 # 系统给redis分配的内存即常驻内存，和top 、 ps 等命令的输出一致
  ```

  ```
    used_memory_rss_human:2.70M  # 以人类可读的格式返回系统redis分配的常驻内存top、ps等命令的输出一致
  ```

  ```
    used_memory_peak:934040  # 内存使用的峰值大小
  ```

  ```
    used_memory_peak_human:912.15K
  ```

  ```
  
  ```

  ```
    total_system_memory:1039048704  # 操作系统的总内存 ，以字节（byte）为单位
  ```

  ```
    total_system_memory_human:990.91M 
  ```

  ```
    used_memory_lua:37888  # lua引擎使用的内存
  ```

  ```
    used_memory_lua_human:37.00K
  ```

  ```
  
  ```

  ```
    maxmemory:0  # 最大内存的配置值，0是不限制
  ```

  ```
    maxmemory_human:0B  
  ```

  ```
    maxmemory_policy:noeviction  # 达到最大内存配置值后的策略
  ```

  ```
    
  ```

  ```
  Persistence：RDB和AOF相关信息
  ```

  ```
    rdb_bgsave_in_progress:0   # 标识rdb save是否进行中
  ```

  ```
    rdb_last_bgsave_status:ok        # 上次的save操作状态
  ```

  ```
    rdb_last_bgsave_status:ok        # 上次的save操作状态
  ```

  ```
    rdb_last_bgsave_time_sec:-1        # 上次rdb save操作使用的时间(单位s)
  ```

  ```
    rdb_current_bgsave_time_sec:-1    # 如果rdb save操作正在进行，则是所使用的时间
  ```

  ```
  
  ```

  ```
    aof_enabled:1                    # 是否开启aof，默认没开启
  ```

  ```
    aof_rewrite_in_progress:0        # 标识aof的rewrite操作是否在进行中
  ```

  ```
    aof_last_rewrite_time_sec:-1    # 上次rewrite操作使用的时间(单位s)
  ```

  ```
    aof_current_rewrite_time_sec:-1 # 如果rewrite操作正在进行，则记录所使用的时间
  ```

  ```
    aof_last_bgrewrite_status:ok    # 上次rewrite操作的状态
  ```

  ```
    aof_current_size:0                # aof当前大小
  ```

  ```
  
  ```

  ```
  
  ```

  ```
  Stats：一般统计
  ```

  ```
    evicted_keys:0                    # 因为内存大小限制，而被驱逐出去的键的个数
  ```

  ```
  
  ```

  ```
  
  ```

  ```
  Replication：主从同步信息
  ```

  ```
    role:master                        # 角色
  ```

  ```
    connected_slaves:1                # 连接的从库数
  ```

  ```
    master_sync_in_progress:0        # 标识主redis正在同步到从redis
  ```

  ```
  
  ```

  ```
  
  ```

  ```
  CPU：CPU消耗统计
  ```

  ```
  
  ```

  ```
  Cluster：集群部分
  ```

  ```
    cluster_enabled:0  # 实例是否启用集群模式
  ```

  ```
  
  ```

  ```
  Keyspace：数据库相关统计
  ```

  ```
    db0:keys=4,expires=0,avg_ttl=0  # db0的key的数量,带有生存期的key的数,平均存活时间
  ```

 

 

 

 

 

 

 

 

 

#### 第2集 Redis6.x服务端配置config命令介绍和最大内存配置

**简介： Redis6.x服务端配置config命令介绍**

- config命令介绍（都有默认值）
  - 可以动态地调整 Redis 服务器的配置(configuration)而无须重启
  - config get xxx、config set xxx
- 常用配置

```
daemonize  #后端运行
bind #ip绑定
timeout  #客户端连接时的超时时间，单位为秒。当客户端在这段时间内没有发出任何指令，那么关闭该连接

databases #设置数据库的个数，可以使用 SELECT 命令来切换数据库。默认使用的数据库是 0
save  #设置 Redis 进行rdb持久化数据库镜像的频率。
rdbcompression #在进行镜像备份时，是否进行压缩

slaveof #设置该数据库为其他数据库的从数据库
masterauth  #当主数据库连接需要密码验证时，在这里配置

maxclients  #限制同时连接的客户数量,当连接数超过这个值时,redis 将不再接收其他连接请求,返回error

maxmemory  #设置 redis 能够使用的最大内存，
```

- maxmemory #设置 redis 能够使用的最大内存，
- 备注
  - 防止所用内存超过服务器物理内存， maxmemory限制的是Redis实际使用的内存量， 也就是used_memory统计项对应的内存
  - 由于内存碎片率的存在， 实际消耗的内存可能会比maxmemory设置的更大， 实际使用时要小心这部分内存溢出
  - 默认无限使用服务器内存， 为防止极端情况下导致系统内存耗尽， 建议所有的Redis进程都要配置maxmemory
  - 在64bit系统下，maxmemory设置为0表示不限制Redis内存使用，在32bit系统下，maxmemory不能超过3GB

 

- 注意：
  - redis在占用的内存超过指定的maxmemory之后，通过maxmemory_policy确定redis是否释放内存以及如何释放内存

 

 

 

 

 

 

 

 

 

 

#### 第3集 【面试核心】Redis6的key过期时间删除策略你知道多少

**简介：Redis6的key过期时间删除策略你知道多少**

- 背景

  - redis的key配置了过期时间，这个是怎么被删除的
  - redis数据明明过期了，怎么还占用着内存？
  - Redis 就只能用 10G，你要是往里面写了 20G 的数据，会发生什么？淘汰哪些数据

   

- redis key过期策略

  - 定期删除+惰性删除。

     

- Redis如何淘汰过期的keys： set name xdclass 3600

  

  - 定期删除：

    - 隔一段时间，就随机抽取一些设置了过期时间的 key，检查其是否过期，如果过期就删除，
    - 定期删除可能会导致很多过期 key 到了时间并没有被删除掉，那咋整呢，所以就是惰性删除

     

  - 惰性删除 ：

    - 概念：当一些客户端尝试访问它时，key会被发现并主动的过期

    - 放任键过期不管，但是每次从键空间中获取键时，都检查取得的键是否过期，如果过期的话，就删除该键

       

  

- Redis服务器实际使用的是惰性删除和定期删除两种策略：通过配合使用这两种删除策略，服务器可以很好地在合理使用CPU时间和避免浪费内存空间之间取得平衡。

 

- 问题
  - 如果定期删除漏掉了很多过期 key，然后你也没及时去查，也就没走惰性删除，此时会怎么样？
  - 如果大量过期 key 堆积在内存里，导致 redis 内存块耗尽了，就需要走内存淘汰机制

 

- 设计缓存中间件：可以参考redis的key过期淘汰方式和内存不足淘汰方式

 

 

 

 

 

#### 第4集 【面试核心】内存不足时-Redis的Key淘汰策略你知道多少

**简介：内存不足时-Redis的Key内存淘汰策略你知道多少**

- 背景

  - redis在占用的内存超过指定的maxmemory之后，
  - 通过maxmemory_policy确定redis是否释放内存以及如何释放内存
  - 提供多种策略

- 策略

  - volatile-lru(least recently used)
    - 最近最少使用算法，从设置了过期时间的键中选择空转时间最长的键值对清除掉；
  - volatile-lfu(least frequently used)
    - 最近最不经常使用算法，从设置了过期时间的键中选择某段时间之内使用频次最小的键值对清除掉；
  - volatile-ttl
    - 从设置了过期时间的键中选择过期时间最早的键值对清除 (删除即将过期的）
  - volatile-random
    - 从设置了过期时间的键中，随机选择键进行清除；
  - allkeys-lru
    - 最近最少使用算法，从所有的键中选择空转时间最长的键值对清除；
  - allkeys-lfu
    - 最近最不经常使用算法，从所有的键中选择某段时间之内使用频次最少的键值对清除；
  - allkeys-random
    - 所有的键中，随机选择键进行删除；
  - noeviction
    - 不做任何的清理工作，在redis的内存超过限制之后，所有的写入操作都会返回错误；但是读操作都能正常的进行;

   

- config配置的时候 下划线_的key需要用中横线-

```
127.0.0.1:6379> config set maxmemory_policy volatile-lru
(error) ERR Unsupported CONFIG parameter: maxmemory_policy

127.0.0.1:6379> config set maxmemory-policy volatile-lru
OK
```

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十五章 【高级篇】Redis6.X高可用之主从复制+读写分离

 

#### 第1集 Redis6.X主从复制+读写分离介绍

**简介：Redis6.X主从复制+读写分离介绍**

- 背景

  - 单机部署简单，但是可靠性低，且不能很好利用CPU多核处理能力

  - 生产环境-必须要保证高可用-一般不可能单机部署

  - 读写分离是可用性要求不高、性能要求较高、数据规模小的情况；

     

- 目标

  - 读写分离，扩展主节点的读能力，分担主节点读压力
  - 容灾恢复，一旦主节点宕机，从节点作为主节点的备份可以随时顶上来

 

- Redis主从架构介绍

 

![image-20210417103309368](https://file.xdclass.net/note/2021/redis/img/image-20210417103309368.png)

 

 

 

 

 

 

 

 

 

#### 第2集 Linux服务器-Redis6.X 主从复制 一主二从架构环境准备

**简介：Redis6.X 主从复制 1主2从架构环境准备**

 

![image-20210417104752208](https://file.xdclass.net/note/2021/redis/img/image-20210417104752208.png)

 

- 配置

```
mkdir -p /data/redis/master/data 
mkdir -p /data/redis/slave1/data 
mkdir -p /data/redis/slave2/data

#从节点开启只读模式(默认)
replica-read-only yes
#从节点访问主节点的密码，和requirepass一样
masterauth 123456
#哪个主节点进行复制
replicaof 8.129.113.233 6379
```

- 创建主配置文件redis.conf

```
bind 0.0.0.0
port 6379
daemonize yes

requirepass "123456"

logfile "/usr/local/redis/log/redis1.log"
dbfilename "xdclass1.rdb"
dir "/usr/local/redis/data"
appendonly yes
appendfilename "appendonly1.aof"
masterauth "123456"
```

- 创建两个从配置文件redis.conf

```
bind 0.0.0.0
port 6380
daemonize yes
requirepass "123456"
logfile "/usr/local/redis/log/redis2.log"
dbfilename "xdclass2.rdb"
dir "/usr/local/redis/data"
appendonly yes
appendfilename "appendonly2.aof"
replicaof 8.129.113.233 6379
masterauth "123456"
```

- 创建从配置文件redis.conf

```
bind 0.0.0.0
port 6381
daemonize yes
requirepass "Wangce9264@"
logfile "/usr/local/redis/log/redis3.log"
dbfilename "redis3.rdb"
dir "/usr/local/redis/data"
appendonly yes
appendfilename "appendonly3.aof"
replicaof 118.31.251.209 6379
masterauth "Wangce9264@"
```

- 防火墙记得关闭，或者开放对应的端口
  - 阿里云服务器记得开发网络安全组

 

 

 

 

 

 

 

#### 第3集 Redis6.X 主从复制 一主二从架构搭建实战

**简介：Redis6.X 主从复制 1主2从架构搭建实战**

- 启动

```
#启动主
./redis-server /data/redis/master/data/redis.conf


#启动从
./redis-server /data/redis/slave1/data/redis.conf

#启动从
./redis-server /data/redis/slave2/data/redis.conf
```

- info replication 查看状态
- 主从复制和读写验证
- 防火墙和网络安全组记得开放端口
  - 6379 主节点
  - 6380 从节点
  - 6381 从节点

 

 

 

 

 

 

 

 

 

 

#### 第4集 Redis6.X主从架构-复制读写分离原理解析

**简介：Redis6.X主从复制-读写分离原理解析**

- 主从复制分两种（主从刚连接的时候，进行全量同步；全同步结束后，进行增量同步）
  - 全量复制
    - master服务器会开启一个后台进程用于将redis中的数据生成一个rdb文件
    - 主服务器会缓存所有接收到的来自客户端的写命令，当后台保存进程 处理完毕后，会将该rdb文件传递给slave服务器
    - slave服务器会将rdb文件保存在磁盘并通过读取该文件将数据加载到内存
    - 在此之后master服务器会将在此期间缓存的命令通过redis传输协议发送给slave服务器
    - 然后slave服务器将这些命令依次作用于自己本地的数据集上最终达到数据的一致性
  - 增量复制
    - Slave初始化后开始正常工作时主服务器发生的写操作同步到从服务器的过程
    - 服务器每执行一个写命令就会向从服务器发送相同的写命令，从服务器接收并执行收到的写命令

 

- 特点

  - 主从复制对于 主/从 redis服务器来说是非阻塞的，所以同步期间都可以正常处理外界请求

  - 一个主redis可以含有多个从redis，每个从redis可以接收来自其他从redis服务器的连接

  - 从节点不会让key过期，而是主节点的key过期删除后，成为del命令传输到从节点进行删除

    - 从节点开启 sync 看日志

     

- 加速复制

  - 完全重新同步需要在磁盘上创建一个RDB文件，然后加载这个文件以便为从服务器发送数据
  - 在比较低速的磁盘，这种操作会给主服务器带来较大的压力
  - 新版支持无磁盘的复制，子进程直接将RDB通过网络发送给从服务器，不使用磁盘作为中间存储
  - repl-diskless-sync yes (默认是no)

 

- 主从断开重连
  - 如果遭遇连接断开，重新连接之后可以从中断处继续进行复制，而不必重新同步
  - 2.8版本后 部分重新同步这个新特性内部使用PSYNC命令，旧的实现中使用SYNC命令

 

![image-20210417163927866](https://file.xdclass.net/note/2021/redis/img/image-20210417163927866.png)

 

 

 

 

 

 

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十六章 【高级篇】Redis6.X高可用之主从+Sentinel哨兵监控

 

#### 第1集 Redis6.X节点高可用监控之Sentinel介绍

**简介：Redis6.X节点高可用监控之Sentinel介绍**

- 背景

- 前面搭建了主从，当主服务器宕机后，需要手动把一台从服务器切换为主服务器，人工干预费事费力，还会造成一段时间内服务不可用

- 哨兵模式介绍

  - Redis提供了哨兵的命令，是一个独立的进程
  - 原理 哨兵通过发送命令给多个节点，等待Redis服务器响应，从而监控运行的多个Redis实例的运行情况
  - 当哨兵监测到master宕机，会自动将slave切换成master，通过通知其他的从服务器，修改配置文件切换主机

- Sentinel三大工作任务

  - 监控（Monitoring）
    - Sentinel 会不断地检查你的主服务器和从服务器是否运作正常
  - 提醒（Notification）
    - 当被监控的某个 Redis 服务器出现问题时， Sentinel 可以通过 API 向管理员或者其他应用程序发送通知
  - 自动故障迁移（Automatic failover）
    - 当一个主服务器不能正常工作时， Sentinel 会开始一次自动故障迁移操作， 它会将失效主服务器的其中一个从服务器升级为新的主服务器， 并让失效主服务器的其他从服务器改为复制新的主服务器
    - 当客户端试图连接失效的主服务器时， 集群也会向客户端返回新主服务器的地址， 使得集群可以使用新主服务器代替失效服务器

   

- 问题

  - 一个哨兵进程对Redis服务器进行监控，可能会出现问题
  - 一般是使用多个哨兵进行监控，各个哨兵之间还会进行监控，形成多哨兵模式

 

- 多哨兵模式下线名称介绍
  - 主观下线（Subjectively Down， 简称 SDOWN）
    - 是单个 Sentinel 实例对服务器做出的下线判断，比如网络问题接收不到通知等
    - 一个服务器没有在 down-after-milliseconds 选项所指定的时间内， 对向它发送 PING 命令的 Sentinel 返回一个有效回复（valid reply）， 那么 Sentinel 就会将这个服务器标记为主观下线
  - 客观下线（Objectively Down， 简称 ODOWN）
    - 指的是多个 Sentinel 实例在对同一个服务器做出 SDOWN 判断， 并且通过 SENTINEL is-master-down-by-addr 命令互相交流之后， 得出的服务器下线判断
    - 一个 Sentinel 可以通过向另一个 Sentinel 发送 SENTINEL is-master-down-by-addr 命令来询问对方是否认为给定的服务器已下线
    - 客观下线条件只适用于主服务器
  - 仲裁 qurum
    - Sentinel 在给定的时间范围内， 从其他 Sentinel 那里接收到了【足够数量】的主服务器下线报告， 那么 Sentinel 就会将主服务器的状态从主观下线改变为客观下线
    - 这个【足够数量】就是配置文件里面的值，一般是Sentinel个数的一半加1，比如3个Sentinel则就设置为2
    - down-after-milliseconds 是一个哨兵在超过规定时间依旧没有得到响应后，会自己认为主机不可用
    - 当拥有认为主观下线的哨兵达到sentinel monitor所配置的数量时，就会发起一次投票，进行failover

 

 

 

 

 

 

 

 

 

 

 

#### 第2集 Redis6.X节点高可用监控之Sentinel哨兵流程解析和准备

**简介：Redis6.X节点高可用监控之Sentinel哨兵搭建环境准备**

- 核心流程

  - 每秒ping，超过时间不响应 则认为主观下线
  - 满足多个，则认为是客观下线
  - 投票选择主节点
  - 如果没有足够的节点同意master下线，则状态会被移除

- 环境准备

  - 配置3个哨兵，每个哨兵的配置都是一样的
  - 启动顺序 先启动主再启动从，最后启动3个哨兵
  - 哨兵端口是 【26379】记得开放

  ```
  #不限制ip
  ```

  ```
  bind 0.0.0.0
  ```

  ```
  
  ```

  ```
  # 让sentinel服务后台运行
  ```

  ```
  daemonize yes
  ```

  ```
  
  ```

  ```
  # 配置监听的主服务器，mymaster代表服务器的名称，自定义，172.18.172.109 代表监控的主服务器，6379代表端口，
  ```

  ```
  #2代表只有两个或两个以上的哨兵认为主服务器不可用的时候，才会进行failover操作。
  ```

  ```
  sentinel monitor mymaster 172.18.172.109 6379 2
  ```

  ```
  
  ```

  ```
  # sentinel auth-pass定义服务的密码，mymaster是服务名称，123456是Redis服务器密码
  ```

  ```
  sentinel auth-pass mymaster 123456
  ```

  ```
  
  ```

  ```
  #超过5秒master还没有连接上，则认为master已经停止
  ```

  ```
  sentinel down-after-milliseconds mymaster 5000
  ```

  ```
  
  ```

  ```
  #如果该时间内没完成failover操作，则认为本次failover失败
  ```

  ```
  sentinel failover-timeout mymaster 30000
  ```

  - 在目录下创建3个文件sentinel-1.conf、sentinel-2.conf、sentinel-3.conf

  ```
  port 26379
  bind 0.0.0.0
daemonize yes
  pidfile "/var/run/redis-sentinel-1.pid"
  logfile "/var/log/redis/sentinel_26379.log"
  dir "/tmp"
sentinel monitor mymaster 118.31.251.209 6379 2
  sentinel down-after-milliseconds mymaster 5000
  sentinel auth-pass mymaster Wangce9264@
  sentinel failover-timeout mymaster 30000
```
  
  ```
  port 26380
bind 0.0.0.0
  daemonize yes
  pidfile "/var/run/redis-sentinel-2.pid"
  logfile "/var/log/redis/sentinel_26380.log"
dir "/tmp"
  sentinel monitor mymaster 118.31.251.209 6379 2
  sentinel down-after-milliseconds mymaster 5000
  sentinel auth-pass mymaster Wangce9264@
sentinel failover-timeout mymaster 30000
  ```
  
  ```
port 26381
  bind 0.0.0.0
  daemonize yes
  pidfile "/var/run/redis-sentinel-3.pid"
logfile "/var/log/redis/sentinel_26381.log"
  dir "/tmp"
  sentinel monitor mymaster 118.31.251.209 6379 2
  sentinel down-after-milliseconds mymaster 5000
sentinel auth-pass mymaster Wangce9264@
  sentinel failover-timeout mymaster 30000
  ```
  

  
  - 记得创建 /var/log/redis 文件夹
  
 

 

 

 

 

 

 

#### 第3集 Redis6.X高可用实战 主从+Sentinel哨兵集群搭建实战

**简介：Redis6.X高可用实战 主从+Sentinel哨兵集群搭建实战**

- 启动哨兵集群

```
./redis-server /usr/local/redis/conf/sentinel-1.conf --sentinel

./redis-server /usr/local/redis/conf/sentinel-2.conf --sentinel

./redis-server /usr/local/redis/conf/sentinel-3.conf --sentinel
```

- 网络安全组需要开放端口
- 优点
  - 主从可以自动切换，可用性更高
- 缺点
  - 主从切换会丢失短暂数据
  - 主节点的写能力和存储能力受限

 

 

 

 

 

 

#### 第4集 新版SpringBoot/微服务cloud整合Redis主从+Sentinel哨兵

**简介： 新版SpringBoot/微服务cloud整合Redis主从+Sentinel哨兵**

- 注释掉 host和port
- 新增配置

```
sentinel:
  master: mymaster
  nodes: 8.129.113.233:26379,8.129.113.233:26380,8.129.113.233:26381
```

 

![image-20210419122500507](https://file.xdclass.net/Library/Application%20Support/typora-user-images/image-20210419122500507.png)

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十七章 【高级篇】Redis6.X高可用之Cluster集群和分片

 

#### 第1集 Redis6.X节点高可用之Cluster集群介绍

**简介： Redis6.X节点高可用之Cluster集群介绍**

- 背景

  - Sentinel解决了主从架构故障自动迁移的问题
  - 但是Master主节点的写能力和存储能力依旧受限
  - 使用Redis的集群cluster就是为了解决单机Redis容量有限的问题，将数据按一定的规则分配到多台机器

- 什么是集群Cluster

  - 是一组相互独立的、通过高速网络互联的计算机，它们构成了一个组，并以单一系统的模式加以管理
  - 容易和分布式弄混，分布式系统简单的可以认为就一个庞大的系统，进行拆分度多个小系统

   

  - 例子：小滴课堂-老王，去银行存钱
    - Anna小姐姐是窗口一的工作人员，包括取号、开户、存钱、挂失、对公业务等等
    - 问题一
      - Anna小姐姐事情很多导致效率低，就找几个人，每个人负责不同的事情，客户根据需求进行选择，这个就是分布式。
    - 问题二
      - 老帆是负责存钱的，只有一个窗口导致排长队，集群的话就可以搞多个窗口，同时对外提供服务

   

- Redis集群模式介绍

  - Cluster模式是Redis3.0开始推出
  - 采用无中心结构，每个节点保存数据和整个集群状态, 每个节点都和其他所有节点连接
  - 官方要求：至少6个节点才可以保证高可用，即3主3从；扩展性强、更好做到高可用
  - 各个节点会互相通信，采用gossip协议交换节点元数据信息
  - 数据分散存储到各个节点上

![image-20210419150410557](https://file.xdclass.net/note/2021/redis/img/image-20210419150410557.png)

 

 

 

 

 

 

 

 

 

 

#### 第2集 Redis6.X节点高可用之Cluster数据分片和虚拟哈希槽介绍

**简介： Redis6.X节点高可用之Cluster数据分片和虚拟哈希槽介绍**

- 背景

  - 主节点的写能力和存储能力受限
  - 单台机器无法满足需求，因此把数据分散存储到多个机器
  - 类似案例：mysql分库分表

  ![image-20210420113524874](https://file.xdclass.net/note/2021/redis/img/image-20210420113524874.png)

- 常见的数据分区算法

  - 哈希取模
    - 对选择的 partitioning key 计算其哈希值，得到的哈希值就是对应的分区
  - 范围分片
    - 通过确定分区键是否在某个范围内来选择分区
  - 一致性Hash分区
  - redis cluster集群没有采用一致性哈希方案，而是采用【数据分片】中的哈希槽来进行数据存储与读取的

- 什么是Redis的哈希槽 slot

  - Redis集群预分好16384个槽，当需要在 Redis 集群中放置一个 key-value 时，根据 CRC16(key) mod 16384的值，决定将一个key放到哪个桶中

     

- 大体流程

  - 假设主节点的数量为3，将16384个槽位按照【用户自己的规则】去分配这3个节点，每个节点复制一部分槽位
    - 节点1的槽位区间范围为0-5460
    - 节点2的槽位区间范围为5461-10922
    - 节点3的槽位区间范围为10923-16383
    - 注意：从节点是没有槽位的，只有主节点才有
  - 存储查找
    - 对要存储查找的键进行crc16哈希运算,得到一个值，并取模16384，判断这个值在哪个节点的范围区间
    - 假设crc16("test_key")%16384=3000，就是节点一
    - crc16算法不是简单的hash算法，是一种校验算法

![image-20210420115553070](https://file.xdclass.net/note/2021/redis/img/image-20210420115553070.png)

- 使用哈希槽的好处就在于可以方便的添加或移除节点。
  - 当需要增加节点时，只需要把其他节点的某些哈希槽挪到新节点就可以了；
  - 当需要移除节点时，只需要把移除节点上的哈希槽挪到其他节点就行了

 

 

 

 

 

 

 

 

 

 

#### 第3集 Redis6.X节点高可用之Cluster集群环境准备

**简介： Redis6.X节点高可用之Cluster集群环境准备**

- 说明
  - 旧版本的需要使用ruby语言进行构建，新版5之后直接用redis-cli即可
  - 6个节点，三主双从，主从节点会自动分配，不是人工指定
  - 主节点故障后，从节点会替换主节点
- 注意点：
  - 把之前的rdb、aof文件删除
- 节点(网络安全组开放端口)
  - 6381、6382
  - 6383、6384
  - 6385、6386

![image-20210419150410557](https://file.xdclass.net/note/2021/redis/img/image-20210419150410557.png)

- 配置

```
bind 0.0.0.0
port 6381
daemonize yes
requirepass "123456"
logfile "/usr/local/redis/log/redis1.log"
dbfilename "xdclass1.rdb"
dir "/usr/local/redis/data"
appendonly yes
appendfilename "appendonly1.aof"
masterauth "123456"

#是否开启集群
cluster-enabled yes

# 生成的node文件，记录集群节点信息，默认为nodes.conf，防止冲突，改为nodes-6381.conf
cluster-config-file nodes-6381.conf

#节点连接超时时间
cluster-node-timeout 20000

#集群节点的ip，当前节点的ip
cluster-announce-ip 172.18.172.109

#集群节点映射端口
cluster-announce-port 6381

#集群节点总线端口,节点之间互相通信，常规端口+1万
cluster-announce-bus-port 16381
bind 0.0.0.0
port 6386
daemonize yes
requirepass "123456"
logfile "/usr/local/redis/log/redis6.log"
dbfilename "xdclass6.rdb"
dir "/usr/local/redis/data"
appendonly yes
appendfilename "appendonly6.aof"
masterauth "123456"

cluster-enabled yes
cluster-config-file nodes-6386.conf
cluster-node-timeout 20000
cluster-announce-ip 172.18.172.109
cluster-announce-port 6386
cluster-announce-bus-port 16386
```

 

 

 

 

 

 

 

 

 

 

#### 第4集 Redis6.X节点高可用之Cluster集群三主三从搭建实战

**简介： Redis6.X节点高可用之Cluster集群三主三从搭建实战**

- 启动6个节点

```
./redis-server ../conf/cluster/redis1.conf
./redis-server ../conf/cluster/redis2.conf
./redis-server ../conf/cluster/redis3.conf
./redis-server ../conf/cluster/redis4.conf
./redis-server ../conf/cluster/redis5.conf
./redis-server ../conf/cluster/redis6.conf
```

- 加入集群(其中一个节点执行即可)
  - --cluster 构建集群全部节点信息
  - --cluster-replicas 1 主从节点的比例，1表示1主1从的方式

```
./redis-cli -a 123456 --cluster create 172.18.172.109:6381 172.18.172.109:6382 172.18.172.109:6383 172.18.172.109:6384 172.18.172.109:6385 172.18.172.109:6386 --cluster-replicas 1
```

![image-20210420181649249](https://file.xdclass.net/note/2021/redis/img/image-20210420181649249.png)

- 检查状态信息(其中一个节点执行即可)

```
./redis-cli -a 123456 --cluster check 172.18.172.109:6381
```

 

 

 

 

 

 

 

 

 

 

 

#### 第5集 Redis6.X节点高可用之Cluster集群读写命令实战

**简介： Redis6.X节点高可用之Cluster集群读写命令**

- 集群状态

```
./redis-cli -c -a 123456 -p 6379

#集群信息
cluster info

#节点信息
cluster nodes
```

- 测试集群读写命令set/get
  - key哈希运算计算槽位置
  - 槽在当前节点的话直接插入/读取，否则自动转向到对应的节点
- 操作都是主节点操作，从节点只是备份

 

- 流程解析
  - 启动应用
  - 加入集群
  - 从节点请求复制主节点（主从复制一样）
    - 先全量
    - 再增量

 

 

 

 

 

 

 

#### 第6集 Redis6.X节点高可用之Cluster集群整合SpringBoot2.X

**简介： Redis6.X节点高可用之Cluster集群整合SpringBoot2.X**

- 不在同个网络，所以集群改为阿里云公网ip地址才可以访问

  - 公司开发部署都会用同个网络
  - 配置文件修改

  ```
  #对外的ip
  ```

  ```
  cluster-announce-ip 8.129.113.233   
  ```

  ```
  #对外端口
  ```

  ```
  cluster-announce-port   
  ```

  ```
  #集群桥接端口
  ```

  ```
  cluster-announce-bus-por  
  ```

  - 动态修改配置
    - config set cluster-announce-ip 8.129.113.233

- 连接池添加 (之前添加)

```
   <dependency>
      <groupId>org.apache.commons</groupId>
      <artifactId>commons-pool2</artifactId>
    </dependency>
```

 

- 配置文件（注释Sentinel相关配置）

```
    cluster:
    #命名的最多转发次数
      max-redirects: 3
      nodes: 8.129.113.233:6381,8.129.113.233:6382,8.129.113.233:6383,8.129.113.233:6384,8.129.113.233:6385,8.129.113.233:6386
```

 

 

 

 

 

 

 

 

 

 

 

#### 第7集 Redis6.X高可用之Cluster集群故障自动转移实战和总结

**简介： Redis6.X节点高可用之Cluster集群故障自动转移实战**

- 集群里面有故障怎么办， 我们就来操作一遍

![image-20210421142055739](https://file.xdclass.net/note/2021/redis/img/image-20210421142055739.png)

- 流程
  - kill掉主节点
  - 从节点成为新的master节点
- 命令

```
./redis-cli -c -a 123456 -p 6381

#集群信息
cluster info

#节点信息
cluster nodes
```

 

- 高可用架构总结
  - 主从模式：读写分离，备份，一个Master可以有多个Slaves
  - 哨兵sentinel：监控，自动转移，哨兵发现主服务器挂了后，就会从slave中重新选举一个主服务器
  - 集群： 为了解决单机Redis容量有限的问题，将数据按一定的规则分配到多台机器，内存/QPS不受限于单机，提高并发量。

 

 

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十八章 【高级篇】分布式缓存Redis6.X新特性讲解拓展

 

#### 第1集 新版Redis6核心特性-多线程介绍

**简介： 新版Redis6核心特性介绍-多线程**

- 新版Redis6特性讲解

  - 支持多线程

    - redis6多线程只是用来处理网络数据的读写和协议解析上，底层数据操作还是单线程
    - 执行命令仍然是单线程，之所以这么设计是不想因为多线程而变得复杂，需要去控制 key、lua、事务，LPUSH/LPOP 等等的并发问题
    - 默认不开启

    ```
    io-threads-do-reads yes
    ```

    ```
    io-threads 线程数
    ```

    - 官方建议 ( 线程数小于机器核数 )
      - 4 核的机器建议设置为 2 或 3 个线程
      - 8 核的建议设置为 4或6个线程，

  - 开启多线程后，是否会存在线程并发安全问题？

  - 不会有安全问题，Redis 的多线程部分只是用来处理网络数据的读写和协议解析，执行命令仍然是单线程顺序执行。

   

 

 

 

 

 

 

 

 

 

 

 

 

#### 第2集 新版Redis6核心特性-Access Control List权限控制

**简介： 新版Redis6核心特性介绍-acl 权限控制**

- 引入了 ACL（Access Control List)

  - 之前的redis没有用户的概念，redis6引入了acl

  - 可以给每个用户分配不同的权限来控制权限

  - 通过限制对命令和密钥的访问来提高安全性，以使不受信任的客户端无法访问

  - 提高操作安全性，以防止由于软件错误或人为错误而导致进程或人员访问 Redis，从而损坏数据或配置

  - 文档：https://redis.io/topics/acl

  - 常用命令

    - acl list 当前启用的 ACL 规则
    - acl cat 支持的权限分类列表
    - acl cat hash 返回指定类别中的命令
    - acl setuser 创建和修改用户命令
    - acl deluser 删除用户命令

    ```
    +<command> 将命令添加到用户可以调用的命令列表中，如+@hash
    ```

    ```
    -<command> 将命令从用户可以调用的命令列表中移除
    ```

    ```
    
    ```

    ```
    #切换默认用户
    ```

    ```
    auth default 123456
    ```

    ```
    
    ```

    ```
    
    ```

    ```
    #例子 密码 123 ，全部key，全部权限
    ```

    ```
    acl setuser jack on >123 ~* +@all
    ```

    ```
    
    ```

    ```
    #例子 密码 123 ，全部key，get权限
    ```

    ```
    acl setuser jack on >123 ~* +get
    ```

| 参 数   | 说明                                                         |
| ------- | ------------------------------------------------------------ |
| user    | 用户                                                         |
| default | 表示默认用户名，或则自己定义的用户名                         |
| on      | 表示是否启用该用户，默认为off（禁用）                        |
| #...    | 表示用户密码，nopass表示不需要密码                           |
| ~*      | 表示可以访问的Key（正则匹配）                                |
| +@      | 表示用户的权限，“+”表示授权权限，有权限操作或访问，“-”表示还是没有权限； @为权限分类，可以通过 `ACL CAT` 查询支持的分类。+@all 表示所有权限，nocommands 表示不给与任何命令的操作权限 |

 

 

 

 

 

 

 

 

 

 

 

#### 第3集 新版Redis6核心特性-Client-Side-Caching 客户端缓存

**简介： 新版Redis6核心特性介绍-客户端缓存**

- 新版Redis6特性讲解

  - client side caching客户端缓存
    - 类似浏览器缓存一样
      - 在服务器端更新了静态文件（如css、js、图片），能够在客户端得到及时的更新，但又不想让浏览器每次请求都从服务器端获取静态资源
      - 类似前端的-Expires、Last-Modified、Etag缓存控制
  - 文档：https://redis.io/topics/client-side-caching

  ![image-20210421135417429](https://file.xdclass.net/note/2021/redis/img/image-20210421135417429.png)

   

  - 详细: 分为两种模式

    ```
    redis在服务端记录访问的连接和相关的key， 当key有变化时通知相应的应用
    ```

    ```
    应用收到请求后自行处理有变化的key, 进而实现client cache与redis的一致
    ```

    ```
    这需要客户端实现，目前lettuce对其进行了支持
    ```



- 默认模式
  - Server 端全局唯一的表（**Invalidation Table**）记录每个Client访问的Key，当发生变更时，向client推送数据过期消息。
    - 优点：只对Client发送其访问过的被修改的数据
    - 缺点：Server端需要额外存储较大的数据量。



- 广播模式
  - 客户端订阅key前缀的广播，服务端记录key前缀与client的对应关系。当相匹配的key发生变化时通知client。
  - 优点：服务端记录信息比较少
  - 缺点：client会收到自己未访问过的key的失效通知

 

 

 

 

 

![logo](https://file.xdclass.net/note/2020/javaweb/%E5%9B%BE%E7%89%87/logo.png) **愿景："让编程不再难学，让技术与生活更加有趣"**

**更多架构课程请访问 xdclass.net**

### 第十九章 全方位Redis6.x之战超多案例+最佳实践专题课程总结

 

#### 第1集 全方位Redis6.x之战超多案例+最佳实践专题课程总结

**简介：全方位Redis6.x之战超多案例+最佳实践专题课程总结**

- Redis常见数据结构和最佳实践
- SpringBoot项目整合+SpringCache实战
- 高可用-主从架构、Sentinel集群
- 高可用-Cluster集群+数据分片
- 新版Redis6新特性

![image-20210421142820451](https://file.xdclass.net/note/2021/redis/img/image-20210421142820451.png)

- Redis的还有很多知识+实战，基本任何一个高并发项目都离不开
  - Redis入侵云服务器、挖矿、勒索比特币等
  - Redisson分布式锁
  - 秒杀系统、优惠券系统实战等
- 综合项目大课训练营 -笔记查看（不对外提供，【原创资料】）
  - 给个学习建议，大课推出的目的，也是很多同学需要这个
  - https://detail.tmall.com/item.htm?id=634842400121

 



 

 

 

 

 

 

 

#### 第2集 架构师成长路线- 如何选择IT技术人的职场充电站

**简介：小滴课堂架构师学习路线和大课训练营介绍**

- 小滴课堂永久会员 & 小滴课堂年度会员

  - 适合IT后端人员，零基础就业、在职充电、架构师学习路线-专题技术方向

    - 包括业界主流技术栈，前端、后端、测试、架构等等课程，接近上百套视频，深度+广度
    - 包括 从零基础到就业班，高级工程师、技术负责人、架构师技术栈 全套学习路线
    - 永久会员可以观看全部专题IT技术，作为一个终生学习平台，每个月更新多套视频
    - 如何获取最新路线图，有你想学的多数主流技术栈，持续更新！！！

  - 学后水平：一线城市 15~25k

  - 适合人员：校招、应届生、培训机构出、工作1~10年的同学都适合

    ![image-20210421141938063](https://file.xdclass.net/note/2021/redis/img/image-20210421141938063.png)

  - 学到技术，涨薪是关键，付出肯定会有收获，未来 一定是持续学习的人

  - 我也在学习每年参加各种技术沙⻰和内部分享会投 入超过10万+，但是我认为是值的，且带来的收益更 大

   

- 大课综合训练营

  - 适合用于专项拔高，适合有一定工作经验的同学，架构师方向发展的训练营，包括多个方向

    - 综合项目大课训练营
      - https://detail.tmall.com/item.htm?id=634842400121
    - 海量数据分库分表大课训练营
    - 架构解决方案大课训练营
    - 全链路性能优化大课训练营
    - 安全攻防大课训练营
    - 数据分析大课训练营
    - 算法刷题大课训练营

    

- 直播小班课（留意官网即可或者联系我即可）



- 技术人的导航站（涵盖我们主流的技术网站、社区、工具等等，即将上线）
  - 地址：open1024.com
  - 地址：xdclass.net

 

![image-20210421143515942](https://file.xdclass.net/note/2021/redis/img/image-20210421143515942.png)

 

![WechatIMG1](https://file.xdclass.net/note/2020/%E6%96%B0%E7%89%88ssm/%E5%9B%BE%E7%89%87/WechatIMG1.png)



**小滴课堂，愿景：让编程不在难学，让技术与生活更加有趣**

**相信我们，这个是可以让你学习更加轻松的平台，里面的课程绝对会让你技术不断提升**

**欢迎加小D讲师的微信： xdclass-lw**

我们官方网站：[https://xdclass.net](https://xdclass.net/)

**千人IT技术交流QQ群： 718617859**

重点来啦：加讲师微信 免费赠送你干货文档大集合，包含前端，后端，测试，大数据，运维主流技术文档（持续更新）

https://mp.weixin.qq.com/s/qYnjcDYGFDQorWmSfE7lpQ