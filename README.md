灵动书城 毕设级别项目开源供大家学习交流  
writer:Beaten_LCU 
2024-06-18  
该部分为说明文档  
技术栈 springMvc+spring+myBatis+maven  
java 保存后端中需要的文件  
bean 封装实体类 每一个实体类对应着数据库中的每一张表 属性就是数据库中的字段  
config 保存配置文件  jdbc 它主要是对数据库连接的配置  
mybatis 文件 对mapper.xml文件进行扫描  
spring,.xml 是配置组件扫描器加载外部的properties文件和配置数据库连接池  
mvc是主要对视图解析器的配置  
controller 导入service层  调用service里面的方法  
controller会接收前端传来的参数来进行业务的操作，然后再返回一个指定的路径  
filter adminfiter 功能主要是做拦截功能， 用户登录后会存入session，当路径包含admin的时候，会进行拦截判断取出session，session为空就拦截，拒绝访问并且并且跳转首页，session不为空且权限为管理员，就不拦截  
mapper文件主要是对数据库进行数据持久化的操作，其方法语句都是针对数据库操作的  
xml文件中的sql语句就是针对数据库操作的具体的实现  
service则是业务处理和数据库的一些处理，有接口也有方法  
utils就是工具类  
Webapp存放前端需要的文件  
admin下面的css,img，js是后台页面的静态资源，下面的jsp就是后台页面  
下面的css，js和images，是前台需要的静态资源。下面的jsp就是前台页面  
error是错误页面  
fonts是字体央视  
layer是layui下的一个web弹层组件，webxml是配置filter和servlet和欢迎界面等等
