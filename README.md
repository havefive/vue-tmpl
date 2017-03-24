# vue-tmpl

vue-cli + vue-router + element-ui + axios,enjoy Vue!

如何快速搭建一个vue项目？这里提供一种方案，基于vue-cli,加入了路由管理vue-router,ui加入饿了么前端库（也可以使用vue-material）,ajax采用最近热门的axios,module使用参考各自的readme，很简单，很快速进行开发……^_^


<p align="center">
  <img src="screenshot/Capture0.png">
</p>


## 步骤 Steps:

### 全局安装vue-cli Install vue-cli
```
$ npm install -g vue-cli
```
For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
=======

### 新建一个项目 Init one project

```
vue init webpack vue-tmpl

cd vue-tmpl

npm install
```

### 安装模块 Add modules(router:vue-router,UI:element-ui,Ajax/Data:axios)

```
npm install vue-router element-ui axios --save
```
### 编辑入口文件 Edit main.js,config router,add page as usual way
```
// code as you wish
```
### 开始开发 Start dev ,打开浏览器 open browser http://localhost:8080

```
npm run dev
```
### 生成上线文件 Build product,will be found at ‘dist’ folder
```
npm run build
```
