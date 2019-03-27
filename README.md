## 20170907： 【Shiro】Shiro从小白到大神(一)-Shiro入门 

Apache Shiro（日语堡垒（Castle）的意思）是一个强大易用的Java安全框架，提供了认证、授权、加密和会话管理功能，可为任何应用提供安全保障 - 从命令行应用、移动应用到大型网络及企业应用。 

## 20170908： 【Shiro】Shiro从小白到大神(二)-Subject认证结合MySQL

Subject认证主体包含两个信息 Principals 身份，可以是用户名，邮件，手机号码等等，只要能用来标识一个登陆主体身份的东西都可以 Credentials 凭证(比如你说你叫张三，你凭什么说叫张三，你这个时候会拿出身份证说你就是叫张三，这个凭证和身份证差不多)，常见有密码，数字证书等等

## 20170909： 【Shiro】Shiro从小白到大神(三)-权限认证(授权) 

Subject认证主体包含两个信息 Principals 身份，可以是用户名，邮件，手机号码等等，只要能用来标识一个登陆主体身份的东西都可以 Credentials 凭证(比如你说你叫张三，你凭什么说叫张三，你这个时候会拿出身份证说你就是叫张三，这个凭证和身份证差不多)，常见有密码，数字证书等等 

## 20171001： 【Shiro】Shiro从小白到大神(四)-集成Web

本节讲集成Web(没有通过数据库-通过text) 实现登录经过Shiro验证后跳转另外的页面，以及没验证通过进行的权限拦截

## 20171212： 【Shiro】Shiro从小白到大神(五)-自定义Realm 

前面讲的，用户数据，以及配置ini数据都是在文件里面配置的，实际项目中，很少这么开发的。基本上是通过读取数据库来配置的。这个时候就需要用到自定义Realm了。

xxxxxxxxxx hibernate.dialect = org.hibernate.dialect.MySQLDialecthibernate.show_sql = falsehibernate.format_sql = falsehibernate.hbm2ddl.auto = nonehibernate.cache.use_second_level_cache = falsehibernate.cache.use_query_cache = falsehibernate.current_session_context_class=threadhibernate.cache.region.factory_class = org.hibernate.cache.ehcache.EhCacheRegionFactoryhibernate.cache.provider_configuration_file_resource_path = ehcache.xmlproperties

