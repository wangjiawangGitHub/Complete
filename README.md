# News client
新闻毕设客户端
=========================================
## 大体介绍：
该项目为一个新闻客户端，数据来源于服务端News-server（使用本地服务器tomcat）,客户端根据选择category与page来获取相应的新闻数据。存在网络（局域网）时，数据通过网络请求获取；网络不存在时，数据从缓存中获取。
## 1.使用技术
### mvp+dagger2.0+retrofit2.0+rxjava2.0
## 2.实现功能
### 1>新闻推荐  （这里只展示某一新闻类型进行显示，未含有推荐算法）
### 2>新闻分类  （将新闻分为不同模块分别进行展示）
### 3>缓存实现  （断网情况下数据从数据库中获取）
### 4>新闻文章
### 5>新闻图集
### 6>历史记录   (待实现)
### 7>浏览历史   (待实现)

## 3.成果展示
<img src="https://github.com/wangjiawangGitHub/News-client/blob/master/1.jpg" width="30%" height="30%" /> —————————————— <img src="https://github.com/wangjiawangGitHub/News-client/blob/master/2.jpg" width="30%" height="30%" />

## 4.使用限制
本客户端需要启动本地服务器来可以获取数据，所以需要News-Server,地址如下
https://github.com/wangjiawangGitHub/News-server


