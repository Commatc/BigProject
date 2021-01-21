# 互联网软件开发技术与实践大作业

#### 介绍
基于SpringBoot+Mybatis+Mysql+中间件构建的商城秒杀系统；其中，中间件主要包括：缓存中间件Redis、消息中间件RabbitMQ、统一协调调度中心中间件ZooKeeper、综合中间件Redisson等等。



#### 开发软件与工具
IntelliJ IDEA 2020.2.3

#### 开发环境

| JDK  | Mysql | Redis | RabbitMQ |
| ---- | ----- | ----- | -------- |
| 1.8  | 5.6   | 3.2   | 3.7.10   |

#### 使用说明

1. 下载代码 git clone将项目下载到IDEA里面
2. 运行sql文件夹下的sql文件
3. 到src/main/resources下的application.properties下修改数据库链接用户名与密码
4. 安装Redis、Mysql、RabbitMQ、Maven等环境
5. 启动前，检查配置 application.properties 中相关Redis、Mysql、RabbitMQ地址
6. 在数据库秒杀商品表里面设置合理的秒杀开始时间与结束时间
7. 登录地址：http://localhost:8080/login/to_login

