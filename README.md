# 基于vue和websocket的多人在线聊天室

### 知识结构
> * nodejs
> * express 
> * websocket 
> * socketio websocket
> * vue + router 
> * es6
> * less
> * iconfont

### 代码架构
* server 运行在node服务器上的js文件，监听websocket连接
* src/api/client 客户端连接服务器的核心js
* src/components 页面的组件,包含login组件(登录页面)，chat组件（聊天页面），groupinfo组件（群信息页面）

### 运行代码
* install dependencies
> npm install

* serve with hot reload at localhost:8080
> npm run dev

* build for production with minification
> npm run build
