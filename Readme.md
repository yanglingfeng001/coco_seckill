# 互联网软件开发课程项目开发手册：

## 开发工具：

IntelliJ IDEA + Navicat + Git + Chrome+Postman

## 开发技术：


前端技术 ：Bootstrap + jQuery + Thymeleaf

后端技术 ：SpringBoot + MyBatis + MySQL

中间件技术 : Druid + Redis + RabbitMQ + Guava

## 压力测试工具：

JMeter

## 部署说明：

- 下载sql文件夹中seckill.sql，导入到本地，数据库名为myseckill，其他参数默认
- 修改application.properties中mysql的url，rabbitmq配置以及redis配置
- 不要更改默认端口
- 启动MainApplication，打开浏览器输入localhost:8080/login/to_login进入到登录页面
- 输入localhost:8080/goods/to_list查看商品列表

