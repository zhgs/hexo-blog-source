---
title: spring boot(一) 入门篇
date: 2018-07-23 16:41:08
tags:spring boot,技术
---
## spring boot介绍
### 依赖(学习前需要了解清楚)
* By default, Spring Boot 1.5.15.BUILD-SNAPSHOT requires Java 7 and Spring Framework 4.3.18.RELEASE or above. You can use Spring Boot with Java 6 with some additional configuration. See Section 85.11, [“How to use Java 6”](https://docs.spring.io/spring-boot/docs/1.5.15.BUILD-SNAPSHOT/reference/htmlsingle/#howto-use-java-6) for more details. Explicit build support is provided for Maven (3.2+), and Gradle 2 (2.9 or later) and 3.  我使用idea创建项目只能选2.0版本，建议springboot 2+ jdk1.8

### what is spring boot?（what)
java发展至今，经久不衰，我觉得spring和android起了很大的作用，spring framework经历了十几年的发展，大家都经历过繁琐的xml配置，spring设计中有个理念“约定大于配置",spring boot诞生了，基于这个理念，让java开发人员不再需要定义样板化的配置，就像maven库存一样整合了所有的jar包，spring boot汇总并简化了所有架构。简单来说：使用spring不再需要繁琐的配置了。

### 使用spring boot有什么好处?（Why）
其实就是简单、快速、方便！平时我们需要搭建一个spring web项目的时候需要怎么做？

* 配置web.xml，集成加载spring各模块
* 配置数据库连接、事务
* 配置加载配置文件的类、开启注解
* 配置日志文件
* 部署tomcat
等等一系列操作

现在非常流行微服务，如果我这个项目仅仅只是需要发送一个邮件，如果我的项目仅仅是生产一个积分；我都需要这样折腾一遍!

但是如果使用spring boot呢？
很简单，我仅仅只需要非常少的几个配置就可以迅速方便的搭建起来一套web项目或者是构建一个微服务！


## 快速入门(How)
一起来动手试试吧

### 新建项目
新建项目有两种方式

* [springboot官网](http://start.spring.io/) 勾选参数自动生成工程，如下图

	![](spring-boot-一-入门篇/01.gif)

* idea新建springboot项目

	![](spring-boot-一-入门篇/02.gif)



## 参考资料
* [牛博](https://www.cnblogs.com/ityouknow/p/5662753.html)
* [开源电子书 ityouknow](https://boot.ityouknow.com)
* [官方文档](https://spring.io/projects/spring-boot#learn)
* spring boot入门视频

	>链接: https://pan.baidu.com/s/1pL84paN 密码: mid4
* spring boot实战视频

	>链接: https://pan.baidu.com/s/1pMoBRi7 密码: 2x4c
* [Spring Boot 中文索引](http://springboot.fun)
* [github托管代码](https://github.com/zhgs/spring-boot-examples)