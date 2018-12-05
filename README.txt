主要特征:

使用宽松的New BSD License协议
速度快，安装简单
支持10种国家和地区语言
插件系统：允许任何人开发自己的插件
模板系统：可以定制自己的模板
系统
可以配置多个主机，每个主机可以有多个管理员
需要管理员密码才能登入操作，确保数据库的安全性
服务器
服务器信息 (WEB服务器, PHP, PHP.ini相关指令 ...)
状态
数据库信息
数据库
查询，创建和删除
执行命令和Javascript代码
统计信息
用户管理
Profile
数据转移
导入导出
集合（相当于表）
强大的查询工具
读数据，写数据，更改数据，复制数据，删除数据
查询、创建和删除索引
清空数据
批量删除和更改数据
统计信息
改名
导入导出   
Introduction
--------------------------------------
RockMongo is a MongoDB administration tool, written in PHP 5, very easy to install and use.


Installation
--------------------------------------
1. Install PHP runtime environment if you don't have one yet, such like Apache Httpd, Nginx ...
2. Install MongoDB PHP driver (http://us.php.net/manual/en/mongo.installation.php)
3. Download the package from http://rockmongo.com/downloads
4. Unzip the files into your disk, under root of your site
5. Open the config.php with your convenient editor, change host, port, admins and so on to yours
6. Visit the index.php in your browser, for example: http://localhost/rockmongo/index.php
7. Login with admin username and password, which is set "admin" and "admin" as default
8. Play with your MongoDBs!


Upgrade from old version
--------------------------------------
1.Copy all files excluding config.php to your old version directory
2.Done!


Contributors
--------------------------------------
iwind.liu <iwind.liu@gmail.com> Leader
leblanc.simon <leblanc.simon@gmail.com> French translation
Klaus Silveira <klaussilveira@gmail.com> Brazilian translation
bmansion <bmansion@mamasam.net> Some small changes
Vladimir Razuvaev <vladimir.razuvaev@gmail.com> Implement features.
Anton Zering <anton.zering@gmail.com> German translation
Borda Juan Ignacio <juanignacioborda@gmail.com> Panels Layout
Diego Baravalle <diegobaravalle@gmail.com> Spanish Translation


Thanks
--------------------------------------
* Many thanks to led24.de for cute icons. 
* Thank Michal Migurski(<mike-json@teczno.com>) for perfect Services_JSON class.
* Thank OFC,  we borrowed json_format() function to make JSON pretty. 
* Thank jQuery, a popular javascript library.
* Thank snipplr.com for mime types mapping.
* Also thank these guys (Marcin, Tyler, Richard, Idan, ...) who spent their time on
  sending feedbacks and advices to me, and let me know i am not alone. 
* Thank Klaus Silveira for Brazilian translation
* Thank leblanc.simon for French translation

Bugs & Issues
--------------------------------------
Please feel free to report any bugs and issues to me, my email is: iwind.liu@gmail.com .


Source Code Repository
--------------------------------------
Repositories are located at 
  https://github.com/iwind/rockmongo.git


Contributing
--------------------------------------
Somebody who want to contribute to the project, may help us by doing these:
* Translate messages from English to other languages (you can see them in app/langs directory)
* Make donations here: http://rockmongo.com/donation
