项目计划

项目计划开发周期为16天。每天，你需要完成教程中的内容。如果你觉得编写代码难度实在太大，可以参考一下当天在GitHub上的代码。

第N天的代码在https://github.com/michaelliao/awesome-python-webapp/tree/day-N上。比如第1天就是：

https://github.com/michaelliao/awesome-python-webapp/tree/day-01

以此类推。

要预览awesome-python-webapp的最终页面效果，请猛击：

awesome.liaoxuefeng.com

day01
搭建开发环境

首先，确认系统安装的Python版本是2.7.x：

$ python --version
Python 2.7.5
然后，安装开发Web App需要的第三方库：

前端模板引擎jinja2：

$ easy_install jinja2
MySQL 5.x数据库，从官方网站http://dev.mysql.com/downloads/mysql/5.6.html下载并安装，安装完毕后，请务必牢记root口令。为避免遗忘口令，建议直接把root口令设置为password；

MySQL的Python驱动程序mysql-connector-python：

$ easy_install mysql-connector-python

awesome-python-webapp/   <-- 根目录
|
+- backup/               <-- 备份目录
|
+- conf/                 <-- 配置文件
|
+- dist/                 <-- 打包目录
|
+- www/                  <-- Web目录，存放.py文件
|  |
|  +- static/            <-- 存放静态文件
|  |
|  +- templates/         <-- 存放模板文件
|
+- LICENSE               <-- 代码LICENSE

创建好项目的目录结构后，建议同时建立Git仓库并同步至GitHub，保证代码修改的安全。

