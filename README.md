# 乐购项目

## 项目安装
```
npm install
```
### 项目运行
```
npm run serve
```
### 项目打包
```
npm run build
```
### 项目地址：https://github.com/lion0814/mall

### 项目描述：

这是一个前后端分离的电商项目，使用vue-cli脚手架初始化vue项目，运用了Vue全家桶—+ES6+Webpack等前端新技术，采用了模块化，组件化，工程化的模式开发

### 学到的知识：

#### 开发一个项目的流程，方法以及思想

1.学会使用脚手架搭建项目

2.了解了项目的优化技巧

3.熟悉组件化，模块化，工程化的开发模式

4.使用ES6+eslint规范代码

#### 插件或第三方库

1.vue-router开发单页面

2.vuex管理应用组件的状态

3.better-scroll实现页面的滑动效果

4.axios的封装与后端数据的交互

5.vue-lazyload实现图片懒加载

### 项目文件及说明

|     目录/文件     |                             说明                             |
| :---------------: | :----------------------------------------------------------: |
|       dist        |                     项目打包后生成的文件                     |
|   node_modules    |                    npm加载的项目依赖模块                     |
|      public       |                         静态资源目录                         |
|        src        | 存放代码的主要目录，包含了如下几个目录及文件:<br/>assets: 放置一些css和图片，如logo等<br/>components: 用来放置一些公共的组件<br/>router: 路由文件夹，决定页面路由的跳转规则<br/>store: vuex的状态管理文件<br/>network：用来存放项目中发起请求的js文件模块<br/>views：存放页面文件，如首页，分类，购物车等<br/>App.vue:应用组件，我们写的所有组件都是在这个组件之上运行的<br/>common: 存放一些公共的js文件 混入，防抖等 |
|   package.json    |           项目的配置文件，以及一些插件依赖包的信息           |
|  babel.config.js  |                      用来配置一些UI插件                      |
| package-lock.json |                      插件依赖的详细信息                      |
|    .gitignore     |             git相关文件，配置不上传至git库的文件             |
|     README.md     |                 项目的说明文档，markdown格式                 |

### 项目截图

**首页**

<img src="https://gitee.com/lion0814/picgo/raw/master/img/20210220124307.png" alt="image-20210220124259188" style="zoom:80%;" />

<img src="https://gitee.com/lion0814/picgo/raw/master/img/20210220124449.png" alt="image-20210220124449178" style="zoom:80%;" />

**分类页**

<img src="https://gitee.com/lion0814/picgo/raw/master/img/20210220124555.png" alt="image-20210220124555931" style="zoom:80%;" />

**购物车**

<img src="https://gitee.com/lion0814/picgo/raw/master/img/20210220125054.png" alt="image-20210220125054764" style="zoom:80%;" />

**我的**

<img src="https://gitee.com/lion0814/picgo/raw/master/img/20210220125220.png" alt="image-20210220125220516" style="zoom:80%;" />
