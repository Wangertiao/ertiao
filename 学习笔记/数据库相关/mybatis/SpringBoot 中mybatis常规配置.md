# SpringBoot 中mybatis常规配置

## 一、依赖坐标

```
<!-- https://mvnrepository.com/artifact/org.mybatis/mybatis -->
<dependency>
    <groupId>org.mybatis</groupId>
    <artifactId>mybatis</artifactId>
    <version>3.5.6</version>
</dependency>
<!-- JDBC -->
<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>5.1.6</version>
</dependency>
```

## 二、application.properties中配置mybatis

```
#========================数据库相关配置========================================
#jdbc驱动
spring.datasource.driver-class-name =com.mysql.cj.jdbc.Driver
#链接数据库
spring.datasource.url=jdbc:mysql://127.0.0.1/数据库名?useUnicode=true&characterEncoding=utf-8&useSSL=false
#用户名
spring.datasource.username=数据可用户名大部分是root
#密码
spring.datasource.password=数据库密码

#=================================mybatis======================================
#使用阿里巴巴druid数据源，默认使用自带的
spring.datasource.type =com.alibaba.druid.pool.DruidDataSource
#开启控制台打印sql
mybatis.configuration.log-impl=org.apache.ibatis.logging.stdout.StdOutImpl
# mybatis 下划线转驼峰配置,两者都可以  数据库的下划线字段映射到java类 把下划线去掉并把下划线后的首字母大写
#mybatis.configuration.mapUnderscoreToCamelCase=true
mybatis.configuration.map-underscore-to-camel-case=true
#配置扫描  注解开发的话忽略此配置
mybatis.mapper-locations=classpath:mapper/*.xml
#配置全局缓存开关
mybatis.configuration.local-cache-scope= statement
#配置xml的结果别名   注解开发的话忽略此配置
mybatis.type-aliases-package=com.wangce.online.online_xdclass.model.entity
```

## 三、spring boot 启动类增加mapperscan

```
@SpringBootApplication
@MapperScan("com.xxxx.xxxx.xxxx.mapper")
public class OnlineXdclassApplication {

	public static void main(String[] args) {
		SpringApplication.run(xxxxxxxxApplication.class, args);
	}

}
```

## 四、创建mapper接口

```
public interface VideoMapper {
    //    VideoMapper类例子
    @Select("SELECT * FROM video")
    List<Video> getAll();
}
```