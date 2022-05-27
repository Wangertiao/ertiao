**简介：使用nignx搭建图片-文件服务器**

- 图片服务器

  - 学javaweb、node、或者其他基础web项目，基本都是图片上传到项目本身，这个是生成很少用
  - 公司一般会使用图片服务器或者云厂商提供的CDN

- 使用流程

- 前端提交图片->后端处理->存储到图片服务器->拼接好访问路径存储到数据库和范围前端

  ![image-20200805170959885](https://file.xdclass.net/note/2020/nginx/%E5%9B%BE%E7%89%87/image-20200805170959885.png)

- 本地图片上传上去，配置专属访问路径

  ```
  server {
  				 	listen       80;
  				  server_name  aabbccdd.com;
  				  
  				  location /app/img {
  				  		#取别名
  				  		alias /usr/local/software/img/;
  				  }
  }
  ```

  

- 注意

  - 在location / 中配置root目录
  - 在location /path中配置alias虚拟目录， 目录后面的"/"符号一定要带上