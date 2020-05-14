Eureka-Server EurekaServerConfig

EurekaServerConfig 服务端配置大致分为以下几类

1、请求认证相关
https://blog.csdn.net/liuchuanhong1/article/details/54729556

spring-security

 
# 安全认证的配置
security:
  basic:
    enabled: true
  user:
    name:  xxx # 用户名
    password: xxx   # 用户密码
    
 2、请求限流相关
 
 3、获取注册信息请求相关
 
 4、自我保护机制相关
 
 5、注册的应用实例的租约过期相关
 
 6、Eureka-Server 远程节点( 非集群 )读取相关
 
 7、Eureka-Server 集群同步相关