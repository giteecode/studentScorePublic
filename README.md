## 基于Java+Springboot+Vue的学生成绩管理系统(源代码+数据库)125

## 一、系统介绍
本项目前后端分离，本系统分为管理员、教师、学生三种角色

### 1、学生：
- 登录、成绩统计图形可视化、课程表、成绩查询、密码修改、个人信息修改

### 2、教师：
- 成绩统计图形可视化、课程表、成绩查询、成绩录入、成绩导出、密码修改、个人信息修改

### 3、管理员：
- 成绩统计图形可视化、课程表、成绩查询、成绩录入、成绩导出、成绩统计详情、课程录入、用户管理、账号管理、密码修改、个人信息修改

## 二、所用技术

后端技术栈：

- Springboot
- Mybatis
- Mysql
- Maven

前端技术栈：

- Vue 
- Vue-router 
- axios 
- elementui

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上,Maven3.6, node14

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、学生
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
### 2、教师
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
### 3、管理员
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)

## 五、浏览地址

前台访问地址：http://localhost:8080
- 学生账号/密码：3168901101/123456
- 教师账号/密码：3890290/123456
- 管理员账号/密码：root/password

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；
2. 使用IDEA/Eclipse导入项目，若为maven项目请选择maven，等待依赖下载完成；
3. 进入src/main/resources修改application.properties里面的数据库配置
4. com/zjh/sms/StudentMisApplication.java启动项目后端项目
5. vscode或idea打开sms项目
6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址

