# 前端开发环境设置步骤

##1. 安装nodejs##
[下载nodejs](https://nodejs.org/en/)

##2. 安装全局工具包##
```
npm config set registry https://registry.npm.taobao.org/
npm install -g npm bower gulp-cli yo jshint
```
##3. 安装工具包
```
cd D:\xxx\cpm-web
npm install
```
##4. 下载依赖包##
```
cd D:\xxx\cpm-web
bower install
```
##5. 编译##
```
cd D:\xxx\cpm-web
gulp
```
##6. 运行##
```
cd D:\xxx\cpm-web
gulp serve
```
