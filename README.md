#悦读（springboot后台）
项目介绍：项目为个人练习开发，是一个用户登录后可以发布、阅读的平台。

#技术栈：
前端主要技术使用了uni-app，前端实现了微信登录，下拉加载，上拉刷新等功能

后端采用了springboot进行开发，为前端提供所有接口，数据库使用了mysql

#使用说明：
    后端配置好数据库连接就可以，然后也可以不使用jenkins部署，修改完pom文件里的配置直接用命令打包到服务器的docker也可以
      前端uni-app可以使用HBuilderX导入,然后点击重新识别项目类型，就可以识别为uni-app项目，可以使用真机调试等，但是前端还没有appid，
   所以打包后微信登录不可用，在main.js中定义了ctx变量，定义后端服务器ip地址，使用时使用内网穿透
   或者部署到服务器都可以使用后端，我的后端可能会维护不及时，个人项目，我尽力吧，还望各位朋友继续完善，我们一起加油！
#项目截图：

![](http://49.232.43.230:8800/files/68b5b80c-8b50-41e6-8ae7-0210d0b46fbe.jpg)
![](http://49.232.43.230:8800/files/579d7638-d01d-4eab-85a8-0375babc8f7b.jpg)
![](http://49.232.43.230:8800/files/ec80ac77-d56f-4801-842f-39aa35fd0b4a.jpg)
