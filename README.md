# SpringBoot-快速构建基于Spring应用的生产级框架

## 前言(OverView)

随着时代的进步，技术的演进，渐渐地**SpringBoot**成为时下流行最广、应用最多的web框架，使得Java开发人员的开发效率大大提升。
本着**知其然知其所以然**的求知精神，来学习SpringBoot的使用方法以及原理。解释**我们为什么要用它(springboot)**

***

## 优势(Futures)

**来源于官网的解释:** [SpringBoot官网](https://spring.io/projects/spring-boot#overview)
- 可以快速创建独立的Spring应用程序
- 内嵌式的Tomcat、Jetty Web应用服务器
- 通过选择式的**starter**依赖项极简地构建项目
- 自动装配Spring和第三方库  
- 提供可用于生产的特性，如度量标准、健康状况检查和外部化配置(actuator)
- 完全不需要代码生成和XML配置文件

***

## 构建springboot项目

- [使用Spring Initializr构建springboot应用程序](https://start.spring.io/)

![Image file](https://github.com/AwakenCN/Almost-Famous/blob/cd51616fa1e107710994b7bde1af426fb87132d3/famous-static/images/spring-initialize.png?raw=true)

***

## 私人订制专属banner

1. 将目标code在**banner生成器**中生成
2. 将生成后的文本复制粘贴到一个名为**banner.txt**文件中
3. 将**banner.txt**移动到Module中的**resources**目录下
4. 启动SpringBoot程序就可以Console界面看到专属banner了

![Image file](https://github.com/AwakenCN/Almost-Famous/blob/680d858e9a01c2aa79e2f74497db22272983d9c7/famous-static/images/application-banner.png?raw=true)

* [Banner生成器](http://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)
