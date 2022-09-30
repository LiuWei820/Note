# **Webpack简介**

## 1. Webpack是什么

Webpack是一种前端资源构建工具，一个静态模块打包器（module bundler）。在Webpack看来，前端的所有资源文件（js/json/css/img/less/...)都会作为模块处理。

它将根据模块的依赖关系进行静态分析，打包生成对应的静态资源（bundle）

![1664454213065](Webpack.assets/1664454213065.png) 

![1650880946068](Webpack.assets/1650880946068.png) 

## 2. Webpack的五个核心概念

### 1.Entry

**入口（Entry）指示 Webpack以哪个文件为入口起点开始打包，分析构建内部依赖图。**

### 2.Output

**输出(Output)指示webpack打包后的资源bundles输出到哪里去，以及如何命名。**

### 3.Loader 

**webpack本身只能处理js、json等资源，其他资源需要借助oader，webpack才能解析，Loaderr让webpack能够去处理那些非javascript文件（webpack自身只能理解javascript）**

### 4.Plugins

**插件（plugins）可以用于执行范围更广的任务。插件的范围包括，从打包优化和压缩，一直到重新定义环境中的变量等。**

### 5.Mode

**模式(mode)指示webpack使用相应模式的配置**

**开发者模式：development     生产者模式：production**

![1664367725232](Webpack.assets/1664367725232.png) 

## 3.功能介绍

![1664454995476](Webpack.assets/1664454995476.png) 

## 4.开始使用

### 1.资源目录

![1664455043265](Webpack.assets/1664455043265.png) 

### 2.创建文件

![1664456310509](Webpack.assets/1664456310509.png) 

![1664456296081](Webpack.assets/1664456296081.png) 

![1664456327463](Webpack.assets/1664456327463.png) 

![1664456354339](Webpack.assets/1664456354339.png) 

![1664456202804](Webpack.assets/1664456202804.png) 

### 3.下载依赖

![1664455087663](Webpack.assets/1664455087663.png) 

![1664456469011](Webpack.assets/1664456469011.png) 

![1664456556407](Webpack.assets/1664456556407.png) 

![1664456827975](Webpack.assets/1664456827975.png) 

### 4.启用webpack

![1664457526329](Webpack.assets/1664457526329.png) 

![1664457358968](Webpack.assets/1664457358968.png) 

![1664457603646](Webpack.assets/1664457603646.png) 

![1664457552536](Webpack.assets/1664457552536.png) 

![1664457665799](Webpack.assets/1664457665799.png) 

![1664457731853](Webpack.assets/1664457731853.png) 

### 5.观察输出文件

**默认webpack会将文件打包输出到dist目录下，我们查看dist目录下文件情况就好了**

![1664458254774](Webpack.assets/1664458254774.png) 

![1664459289850](Webpack.assets/1664459289850.png) 

![1664459222742](Webpack.assets/1664459222742.png) 

## 5.开发模式介绍

![1664520416164](Webpack.assets/1664520416164.png) 

## 6.处理CSS资源

安装css-loader和style-loader

```bash
npm install --save-dev css-loader
```

![1664522259069](Webpack.assets/1664522259069.png) 

![1664522308119](Webpack.assets/1664522308119.png) 

![1664522341593](Webpack.assets/1664522341593.png) 

![1664522389304](Webpack.assets/1664522389304.png) 

![1664522435440](Webpack.assets/1664522435440.png) 

![1664522448361](Webpack.assets/1664522448361.png) 

## 7.处理less资源

![1664523086299](Webpack.assets/1664523086299.png) 

![1664523099987](Webpack.assets/1664523099987.png) 

![1664523114515](Webpack.assets/1664523114515.png) 

![1664523003640](Webpack.assets/1664523003640.png) 

![1664523073776](Webpack.assets/1664523073776.png) 

![1664523042493](Webpack.assets/1664523042493.png) 

## 8.处理sass资源

![1664526008146](Webpack.assets/1664526008146.png) 

![1664526018625](Webpack.assets/1664526018625.png) 

![1664526091523](Webpack.assets/1664526091523.png) 

![1664526114514](Webpack.assets/1664526114514.png) 

![1664523318235](Webpack.assets/1664523318235.png) 

![1664526144077](Webpack.assets/1664526144077.png) 

![1664525957843](Webpack.assets/1664525957843.png)

## 9.处理stylus资源

![1664526732232](Webpack.assets/1664526732232.png) 

![1664526747698](Webpack.assets/1664526747698.png) 

![1664526366409](Webpack.assets/1664526366409.png) 

![1664526826732](Webpack.assets/1664526826732.png) 

![1664526674304](Webpack.assets/1664526674304.png) 

![1664526656496](Webpack.assets/1664526656496.png) 

## 10.处理图片资源







