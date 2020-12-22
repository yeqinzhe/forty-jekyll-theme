---
layout: post
title: java配置环境变量
description: 天天向上配置java环境变量的笔记
image: assets/images/pic03.jpg
---

1. 通过点击计算机-->属性-->高级-->环境变量

2. 环境变量新建JAVA_HOME（这里填写你的java安装目录）

   
   C:\Program Files\Java\jdk 
   

3. 在PATH 里加上%JAVA_HOME%\bin

   
   %JAVA_HOME%\bin;
   

4.    添加CLASSPATH 环境变量

   
   .;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar
   


   

   






   