# 使用express和mongoose做增删查找

### 首先安装express
见：https://blog.csdn.net/newway007/article/details/105123001

### 安装mongoose 和 mongodb

mongodb我官网上那个下载按钮我点击没动静。。。。也不知道是官网抽了风还是怎么回事，于是我在网上随便找了资源

配置过程：

 cmd打开你解压后的文件夹下的bin文件夹
mongod.exe --logpath C:\Users\86178\Downloads\mongodb\mongodb-win32-x86_64-3.0.6\log\mongodb.log --logappend --dbpath C:\Users\86178\Downloads\mongodb\mongodb-win32-x86_64-3.0.6\data\db --directoryperdb --serviceName MongoDB --install

这句话是将mongodb 加入Windows本地服务中去 ，就可以用net start MongoDB 启动服务了。。

 其中mongodb-win32-x86_64-3.0.6是你解压后的文件夹名称，log文件夹需要你自己创建(日志文件存放处)；同时还要创建data文件夹，以及data下面的db文件夹(作为数据存放目录)；





 

 你也可以直接运行 mongod.exe 使用默认目录； as you like；


 需要关闭mongodb，只需要输入net stop mongodb。。


### 全局安装 supervisor，这没有啥好说的

使用supervisor来启动项目


 不小心把node_modules传上去了。。。。

 可以
 ```
 npm i
 ```

 再：
 ```
 npm run start
 ```


 做一个关于express和mongoose的了解吧。。。。。感觉这个是之前前后端没有分离时做的东西。。。


