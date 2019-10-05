# SpringBoot-自动装配原理及源码分析

## 前言(OverView)

本文内容主要阐述SpringBoot特性之自动装配。

- 

## 介绍

### 何为自动装配:


### 如何开启自动装配？

使用注解 **@SpringBootApplication**，如图:

![Image file](https://github.com/AwakenCN/Almost-Famous/blob/47b61fcb33433b5a1ff5b0c6b5821e422ab21ac8/famous-static/images/springbootApplication.png?raw=true)

### spring.factories

![Image file](https://github.com/AwakenCN/Almost-Famous/blob/3a778fa5b0d25003227e4efabd52024dfa6340f9/famous-static/images/spring-factories.png?raw=true)

- #Initializers
- Application Listeners
- Auto Configuration Import Listeners
- Auto Configuration Import Filters
- Auto Configure
- Failure analyzers
- Template availability providers

## SpringBoot自动装配的源码分析

探究SpringBoot自动装配的源码分析的同时，我们就不得不说**spring-content组件**与**AutoConfigurationImportSelector.java**这俩部分

![AutoConfiguration自动装配流程图](https://github.com/AwakenCN/Almost-Famous/blob/195d3e1c1de51938971cfb22635279a7ccf6800a/famous-static/images/autoConfiguration-process.png?raw=true)

### spring-content组件

- @Import
- @Configuration
- @ComponentScan


### AutoConfigurationImportSelector.java



## 总结


























