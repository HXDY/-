# -Train ticketing system-
# java 后台管理web端，ionic移动用户端，mysql数据库
#系统使用下载安装 
*1、	移动端APP前端：Visual Studio Code。 
*2、	管理Web与后台：eclipse。 
*3、	数据库管理：Navicat 12 for MySQL。 
*4、	服务器：apache-tomcat-7.0.94。 
#系统使用环境配置步骤 
*1、	安装Android SDK。 
*2、	JDK下载安装并配置相应环境变量，版本：1.8.0_144。 
*3、	安装node.js。 
*4、	安装ionic和Cordova，CMD运行命令：“npm install ionic@ 1.7.16 crodova 6.2.0 -g”。 
# 运行系统步骤 
##一、	数据库建立：
*复制代码文件中的“MySQL文件.sql”文件在Navicat中运行建立数据库。 
##二、	Web管理端和后台： 
*1、	在eclipse软件中新建Dynamic Web Project项目。 
*2、	复制代码文件中的“后台与管理员web端”文件下的“src”和“WebContent” 替换步骤2中新项目的对应文件。 
*3、	将新项目部署到tomcat服务器。 
*4、	启动tomcat服务器，运行“WebContent”文件的“admin.jsp”即可在浏览器中访问管理员web端主页。 
##三、移动端： 
*1、	下载ionic项目模板，在CMD运行命令：“ionic start trainApp tabs”。 
*2、	为项目添加 Android 平台支持，在 CMD 运行命令：“ionic platform add android”。 
*3、	复制代码文件中的“用户APP端”文件下的“www”和“node_modules”替换步骤2生成的模板项目中的对应文件。 
*4、	用 Visual Studio Code 软件打开项目模板文件，再打开 www 目录下的index.html文件，右击使用“Open with Live Server”在浏览器中打开即可进入用户APP主界面。 


