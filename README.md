# vue-tmpl
vue-cli + vue-router + element-ui + axios,enjoy Vue!

如何快速搭建一个vue项目？这里提供一种方案，基于vue-cli,加入了路由管理vue-router,饿了么前端库（或者采用vue-material）,ajax采用最近热门的axios,module使用参考各个的readme.

## Steps:

### Install vue-cli
```
$ npm install -g vue-cli
```

### Init one project

```
vue init webpack vue-tmpl

cd vue-tmpl

npm install
```

### Add modules(router:vue-router,UI:element-ui,Ajax/Data:axios)

```
npm install vue-router element-ui axios --save
```
### Edit main.js,config router,add page as usual way
```
// code as you wish
```
### Start dev

```
npm run start
```
### Build product,will be found at ‘dist’ folder
```
npm run build
```


