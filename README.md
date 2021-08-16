# 基于ssm的图书馆管理系统

## 功能介绍
基于ssm的图书馆管理系统.主要功能包括：图书查询、图书管理、图书编辑、读者管理、图书的借阅与归还以及借还日志记录等。

用户分为两类：读者、图书馆管理员。图书馆管理员可以修改读者信息，修改书目信息，查看所有借还日志等；读者仅可以修改个人信息、借阅或归还书籍和查看自己的借还日志。

## 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。

2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；

## 技术栈
1. 后端：Spring SpringMVC MyBatis

2. 前端：JSP+bootstrap+jQuery

## 使用说明
1. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，下载所需jar包；

2. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
3. 将项目中db.properties配置文件中的数据库配置改为自己的配置
4. 配置tomcat，然后运行项目，输入localhost:8080/ 登录
5. 管理员账户:123456  密码:123456
读者账户：10000 密码：123456

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221248_d112b968_9582680.png "1.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221302_f149dcb6_9582680.png "2.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221315_7f75e611_9582680.png "3.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221325_19aa09de_9582680.png "4.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221336_2d14e3bb_9582680.jpeg "5.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221345_b33aafbb_9582680.jpeg "6.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221355_1eb951d1_9582680.jpeg "7.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221405_547cbe75_9582680.jpeg "8.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221414_a1a33f06_9582680.jpeg "9.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221424_c5ac83ad_9582680.jpeg "10.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221434_bff3a505_9582680.jpeg "11.jpg")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0816/221444_184c44a2_9582680.jpeg "12.jpg")

