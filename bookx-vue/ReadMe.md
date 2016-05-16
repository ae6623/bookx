# bookx-vue
部署说明 QQ 43163707 落雨

1. 安装Nodejs,建议使用5.x 以及以上版本
2. 本项目因为上传到了github，所以node_modules文件夹是没有上传的，需要在clone本工程后，进行npm install即可，大家也不用上传此文件夹，类似于Maven仓库，package.json已经统一管理node_module,需要的可以在里面添加即可
3. 本工程集成了ES6编译器，babel，以及webpack自动化工具，在本工程根路径执行npm run dev 命令，即可自动编译，并启动8080端口，具体配置参照build/webpack.dev.conf.js
4. 本工程试用ES6语法编写js文件，进行开发，由第3步的webpack自动编译
5. vue结尾后缀均为封装的vue组件，推荐这种玩法
6. 还在写。

> A Vue.js project

## Build Setup

``` bash
# cd project
cd bookx-vue

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](https://github.com/vuejs-templates/webpack#vue-webpack-boilerplate) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
