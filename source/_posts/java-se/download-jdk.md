---
title: download-jdk
category: java-se
date: 2022-03-07 20:34:30
tags: java
---

使用Java之前，第一步要为电脑安装JDK。

JDK全称Java Development Kit，即Java开发工具包。

JDK的下载途径有很多，最权威的当然是Oracle官网：[Java Archive | Oracle](https://www.oracle.com/java/technologies/downloads/archive/)

我们可以根据自己的需要选择不同的`版本`和`系统`进行下载：

![](image-20220307210348975.png)

由于官网下载速度比较慢，在此分享几个主要版本的天翼云盘给大家：

# Windows

## 1 安装

### `zip`压缩文件

对于`zip`压缩文件，直接解压缩到任意安装目录（例如：`D:\Environment\jdk-11.0.13`）：

![](image-20220307212630950.png)

### `exe`可执行文件

1. 双击`exe`文件，点击`下一步`：

   ![](image-20220307215303189.png)

2. 点击`更改`，选择任意安装目录（例如：`D:\download\jdk-8`）：

   ![](image-20220307215456243.png)

3. 点击`下一步`，开始安装：

   ![](image-20220307215641490.png)

4. 安装完成后，会提示安装`jre`。由于`jdk`自带`jre`，所以我们在这里点`x`关闭：

   ![](image-20220307215726930.png)

5. 安装完成后，点击`关闭`：

   ![](image-20220307215849725.png)

## 2 设置环境变量

将安装目录下`/bin/`目录（例如：`D:\Environment\jdk-11.0.13\bin`）设置成`path`环境变量的值：

![](image-20220307213226625.png)

## 3 验证

1. 通过`Win`+`R`，打开运行窗口：

   ![](image-20220307213657389.png)

2. 在命令行里输入`java -version`，如果出现Java版本信息，说明安装成功：

   ![](image-20220307213648891.png)

说明：如果在电脑中同时安装多个版本的JDK，默认首先会使用`path`环境变量中位置靠前的版本。

# Linux（待定）

# macOS（待定）
