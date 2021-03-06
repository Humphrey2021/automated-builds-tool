# 自动化构建工具

> 虽然我们可以使用`npm scripts`实现自动化构建，但如果是特别复杂的业务场景，这个就显得有些力不从心了，这时我们就需要借助工具去解决问题
目前市面上常见的自动化构建工具有,Grunt、Gulp
- Grunt
最早的前端构建系统，插件生态非常完善，几乎可以完成自动化构建的任何事情。但由于工作过程是基于临时文件去实现的，所以构建速度相对较慢。它的每一步都会有磁盘读写操作。

- Gulp
基于内存实现的，所以构建速度会非常的快，默认支持同时执行多个任务。目前最流行的自动化构建工具

## Grunt

### Grunt 的基本使用
```shell
yarn init --yes
yarn add grunt
# 创建 grunt 的入口文件
touch gruntfile.js
```
具体使用方式请查看`gurntfile.js`文件

## Gulp
> 高效，易用

### Gulp 的基本使用
```shell
yarn init --yes
yarn add gulp --dev
# 创建 gulp 的入口文件
touch gulpfile.js
```
具体使用方式请查看`gulpfile.js`文件

### 使用 gulp 实现一个小项目

项目地址：[gulp-demo](https://github.com/Humphrey2021/gulp-demo)

### 封装一个自己的工作流
地址: [humphrey-pages](https://github.com/Humphrey2021/humphrey-pages)

可以使用`npm i humphrey-pages`进行安装
