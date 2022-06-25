# 项目名称

SSM框架的包头师范学院教务信息查询系统的设计与实现源码+论文第五稿+代码答疑讲解（包安装配置，已降重）

# 系统介绍
根据上文中对用户需求的一系列综合细致的分析，针对本文基于Java Web的教务信息查询系统，得到模块结构图，如图3-1 所示：

图3-1系统模块结构图

本系统中老师模块实现的功能主要有个人信息的维护即对用户资料的增删改查，和成绩的录入和查询；学生模块实现的功能有个人信息的维护还有成绩的查询；负责后台运营协调的管理员则可以进行对所有用户的信息维护，以及综合管理课程班级信息和学生科目成绩。

# 环境需要

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。\
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;\
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可\
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS； \
5.数据库：MySql 5.7版本；\
6.是否Maven项目：否；

# 技术栈

1. 后端：Spring+SpringMVC+Mybatis\
2. 前端：JSP+CSS+JavaScript+jQuery

# 使用说明

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；\
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;\
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；\
3. 将项目中springmvc-servlet.xml配置文件中的数据库配置改为自己的配置;\
4. 运行项目，在浏览器中输入http://localhost:8080/ 登录

# 高清视频演示

https://www.bilibili.com/video/BV15U4y1Q7gM/

> # **数据库及资料有偿获取：QQ:3484724101**

​