## 一、简介

### 1.1 常用注解

先简单认识下`Mybatis`的常用注解，如下：

- `@Insert`：实现新增
- `@Update`：实现更新
- `@Delete`：实现删除
- `@Select`：实现查询
- `@Result`：实现结果集封装
- `@Results`：可以与`@Result`一起使用，封装多个结果集
- `@One`：实现一对一结果集封装
- `@Many`：实现一对多、多对多结果集封装

### 1.2 核心配置文件

此次采用spingboot项目搭建，只需要在Application文件中加上@MapperScan的注解扫描路径即可

```
@SpringBootApplication
@MapperScan("ertiao_xyz.demo.mapper")
public class WeixinpayApplication {

	public static void main(String[] args) {
		SpringApplication.run(demo.class, args);
	}

}
```

### 1.3 复杂映射

使用注解开发后，我们可以使用`@Results`注解，`@Result`注解，`@One`注解，`@Many`注解组合完成复杂关系的配置

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513163448365.png" alt="image-20220513163448365" style="zoom:33%;" /> 

## 二、基本使用

### 2.1 创建UserMapper接口

创建`UserMapper`接口，提供增删改查方法，如下：

```
@Insert("insert into user values(#{id},#{username},#{password},#{birthday})")
public void save(User user);

@Update("update user set username=#{username},password=#{password} where id=#{id}")
public void update(User user);

@Delete("delete from user where id=#{id}")
public void delete(int id);

@Select("select * from user where id=#{id}")

public User findById(int id);

@Select("select * from user")
public List<User> findAll();
```

### 2.2 测试

编写单元测试，如下：

```
private UserMapper mapper;

@Test
public void testSave(){
    User user = new User();
    user.setUsername("tom");
    user.setPassword("abc");
    mapper.save(user);
}

@Test
public void testUpdate(){
    User user = new User();
    user.setId(18);
    user.setUsername("lucy");
    user.setPassword("123");
    mapper.update(user);
}

@Test
public void testDelete(){
    mapper.delete(18);
}

@Test
public void testFindById(){
    User user = mapper.findById(2);
    System.out.println(user);
}

@Test
public void testFindAll(){
    List<User> all = mapper.findAll();
    for (User user : all) {
        System.out.println(user);
    }
}
```

## 三、一对一查询

### 3.1 模型

用户表和订单表的关系为，一个用户有多个订单，一个订单只从属于一个用户

一对一查询的需求：`查询一个订单，与此同时查询出该订单所属的用户`

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164042260.png" alt="image-20220513164042260" style="zoom:33%;" /> 

### 3.2 语句

对应的sql语句：
`select * from orders;`
`select * from user where id=查询出订单的uid;`

查询的结果如下：

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164106260.png" alt="image-20220513164106260" style="zoom:33%;" /> 

### 3.3 创建Order和User实体类

```
public class Order {    
	private int id;    
	private Date ordertime;    
	private double total;    
	//代表当前订单从属于哪一个客户    
	private User user;
	// 省略get set方法
}
public class User {        
	private int id;    
	private String username;    
	private String password;    
	private Date birthday;
	// 省略get set方法
}
```

### 3.4 创建OrderMapper接口

```
public interface OrderMapper {    
	List<Order> findAll();
}
```

### 3.5 使用注解配置Mapper

创建`UserMapper`接口，提供`findById`方法，如下：

```
@Select("select * from user where id=#{id}")
public User findById(int id);
```

在`OrderMapper`中通过注解获取数据：

```
@Select("select * from orders")
@Results({
        @Result(column = "id",property = "id"),
        @Result(column = "ordertime",property = "ordertime"),
        @Result(column = "total",property = "total"),
        @Result(
                property = "user", //要封装的属性名称
                column = "uid", //根据那个字段去查询user表的数据
                javaType = User.class, //要封装的实体类型
                //select属性 代表查询那个接口的方法获得数据
                one = @One(select = "com.happy.mapper.UserMapper.findById")
        )
})
public List<Order> findAll();
```

这里使用到了`@one`注解，表明是一对一关系，关系图如下：

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164220061.png" alt="image-20220513164220061" style="zoom:33%;" /> 



## 四、一对多

### 4.1 模型

用户表和订单表的关系为，一个用户有多个订单，一个订单只从属于一个用户

一对多查询的需求：`查询一个用户，与此同时查询出该用户具有的订单`

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164312917.png" alt="image-20220513164312917" style="zoom:33%;" /> 

### 4.2 语句

对应的sql语句：
`select * from user;`
`select * from orders where uid=查询出用户的id;`

查询的结果如下：

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164518290.png" alt="image-20220513164518290" style="zoom:33%;" /> 

### 4.3 创建User和Order实体类

```
public class Order {    
	private int id;    
	private Date ordertime;    
	private double total;    
	//代表当前订单从属于哪一个客户    
	private User user;
	// 省略get set方法
}
public class User {        
	private int id;    
	private String username;    
	private String password;    
	private Date birthday;
    //代表当前用户具备哪些订单    
    private List<Order> orderList;
    // 省略get set方法
}
```

### 4.4 创建UserMapper接口

```
List<User> findAllUserAndOrder();
```

UserMapper中findUserAndOrderAll方法配置如下：

```
@Select("select * from user")
@Results({
@Result(id=true ,column = "id",property = "id"),
@Result(column = "username",property = "username"),
@Result(column = "password",property = "password"),
@Result(
property = "orderList",
column = "id",
javaType = List.class,
many = @Many(select = "com.happy.mapper.OrderMapper.findByUid")
)
})
public List findUserAndOrderAll();
```

此处使用`@Many`注解，表明是一对多关系，关系图如下：

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164655170.png" alt="image-20220513164655170" style="zoom:33%;" /> 

## 五、多对多查询

### 5.1 模型

用户表和角色表的关系为，一个用户有多个角色，一个角色被多个用户使用

多对多查询的需求：`查询用户同时查询出该用户的所有角色`
<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164721276.png" alt="image-20220513164721276" style="zoom:33%;" /> 

### 5.2 语句

对应的sql语句：
`select * from user;`
`select * from role r,user_role ur where r.id=ur.role_id and ur.user_id=用户的id`

查询的结果如下
<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164756468.png" alt="image-20220513164756468" style="zoom:33%;" /> 

### 5.3 创建Role实体类，修改User实体类

```
public class Role {    
	private int id;    
	private String rolename;
	// 省略get set方法
}
public class User {    
	private int id;    
	private String username;    
	private String password;    
	private Date birthday;
    //代表当前用户具备哪些订单    
    private List<Order> orderList;
    //代表当前用户具备哪些角色    
    private List<Role> roleList;
    // 省略get set方法
}
```

### 5.4 UserMapper添加方法

```
List<User> findAllUserAndRole();
```

#### 5.5 使用注解配置Mapper

创建`RoleMapper`，提供`findByUid`方法，如下：

```
public interface RoleMapper {
    @Select("SELECT * FROM sys_user_role ur,sys_role r WHERE ur.roleId=r.id AND ur.userId=#{uid}")
    public List<Role> findByUid(int uid);
}
```

`UserMapper`中`findUserAndRoleAll`配置如下：

```
@Select("SELECT * FROM USER")
@Results({
        @Result(id = true,column = "id",property = "id"),
        @Result(column = "username",property = "username"),
        @Result(column = "password",property = "password"),
        @Result(
                property = "roleList",
                column = "id",
                javaType = List.class,
                many = @Many(select = "com.happy.mapper.RoleMapper.findByUid")
        )
})
public List<User> findUserAndRoleAll();
```

此处使用了`@Many`，表明是多对多，关系图如下：

<img src="/Users/ertiao/Library/Application%20Support/typora-user-images/image-20220513164818484.png" alt="image-20220513164818484" style="zoom:33%;" /> 