# Java技术栈笔记

[![reading](https://image.baidu.com/search/detail?ct=503316480&z=undefined&tn=baiduimagedetail&ipn=d&word=%E5%91%A8%E5%86%AC%E9%9B%A8&step_word=&ie=utf-8&in=&cl=2&lm=-1&st=undefined&hd=undefined&latest=undefined&copyright=undefined&cs=68937915,1558979095&os=3109903788,2958222188&simid=0,0&pn=4&rn=1&di=65560&ln=1776&fr=&fmq=1624527144145_R&fm=&ic=undefined&s=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&is=0,0&istype=0&ist=&jit=&bdtype=0&spn=0&pi=0&gsm=0&objurl=https%3A%2F%2Fgimg2.baidu.com%2Fimage_search%2Fsrc%3Dhttp%253A%252F%252Finews.gtimg.com%252Fnewsapp_match%252F0%252F12063797535%252F0.jpg%26refer%3Dhttp%253A%252F%252Finews.gtimg.com%26app%3D2002%26size%3Df9999%2C10000%26q%3Da80%26n%3D0%26g%3D0n%26fmt%3Djpeg%3Fsec%3D1627119143%26t%3Defc4a7557550412ae2bce50bf2f90030&rpstart=0&rpnum=0&adpicid=0&nojc=undefined)]
[![coding](https://badgen.net/badge/leetcode/coding%20together/cyan)]
[![sharing](https://badgen.net/badge/readers/share%20together/cyan)]
[![stars](https://badgen.net/github/stars/doocs/wulimax/reactApp)]
[![forks](https://badgen.net/github/forks/wulimax/reactApp)]
[![contributors](https://badgen.net/github/contributors/wulimax/reactApp)]
[![help-wanted](https://badgen.net/github/label-issues/wulimax/reactApp/help%20wanted/open)]
[![issues](https://badgen.net/github/open-issues/wulimax/reactApp)]
[![PRs Welcome](https://badgen.net/badge/PRs/welcome/green)](http://makeapullrequest.com)

### 内容说明：
左林林个人文档

## 目录

- [java核心知识](#java核心知识)
    - [jvm](#jvm)
    - [security](#security)
    - [并发编程](#并发编程)
    - [基础](#基础)
- [计算机网络](#计算机网络)
    - [IO多路复用分享](#IO多路复用分享)
    - [Linux Epoll原理解析](#LinuxEpoll原理解析)
    - [Socket常见异常](#Socket常见异常)
    - [TCP有限状态机](#TCP有限状态机)
    - [计算机网络教材整理](#计算机网络教材整理)
    - [HTTP2的艺术](#HTTP2的艺术)
    - [HTTPS实践](#HTTPS实践)
    - [当你输入一个网址的时候，实际会发生什么?](#当你输入一个网址的时候，实际会发生什么)
    - [HTTP协议的底层实现](#HTTP协议的底层实现)
    - [BIO\NIO\Epoll\IO复用](#BIO\NIO\Epoll\IO复用)
- [计算机是怎么跑起来的](#计算机是怎么跑起来的)
  - [IO多路复用分享](#IO多路复用分享)
- [开源框架](#开源框架)
    - [spring](#spring)
    - [spring boot](#第四季-海量数据)
    - [spring cloud netflix](#springcloudnetfli)
    - [spring clond alibaba](#第五季-高性能)
    - [netty](#第六季-高可用)
    - [zookeeper](#zookeeper)
    - [elasticsearch](#elasticsearch)
    - [消息中间件](#消息中间件)
    - [Guava](#Guava)
- [技术方案](#技术方案)
  - [DDD领域驱动](#DDD领域驱动)
  - [异地高活](#异地高活)
  - [网关](#网关)
  - [高并发和高可用](#高并发和高可用)
  - [链路追踪](#链路追踪)
- [数据库](#数据库)
  - [mysql](#mysql)
  - [redis](#redis)
- [微服务](#互联网Java进阶面试训练营)
  - [分布式服务治理](#分布式服务治理)
  - [分布式架构基础](#分布式架构基础)
- [系统设计](#系统设计)
- [内功心法](#内功心法)
  - [软件设计原则](#软件设计原则)
  - [设计模式](#设计模式)
  - [算法与数据结构](#算法与数据结构)
- [日常摘录及问题总结](#日常摘录及问题总结)
  - [第一季:分布式](#第一季-分布式)
  - [第二季:高并发](#第二季-高并发)
  - [第三季:微服务](#第三季-微服务)
  - [第四季:海量数据](#第四季-海量数据)
  - [第五季:高性能](#第五季-高性能)
  - [第六季:高可用](#第六季-高可用)
- [DevOps](#互联网Java进阶面试训练营)
  - [Git](#Git)
  - [docker](#docker)
  - [Maven](#Maven)
  - [mybaits](#mybaits)
- [面试专栏](#面试专栏)
  - [石杉面试突击第一季](#石杉面试突击第一季)
  - [石杉面试突击第二季](#石杉面试突击第二季)
  - [石杉面试突击第三季](#石杉面试突击第三季)


## 大纲

### java核心知识
- [jvm](/docs/java-core/jvm.md)
- [security](/docs/java-core/jvm.md)
- [并发编程](/docs/java-core/concurrent.md)
- [基础](/docs/java-core/base.md)
### 计算机网络
- [网络是怎么连接的](/docs/computer/网络是怎么连接的.md)
- [IO多路复用分享](/docs/computer/IO多路复用.md)
- [Linux Epoll原理解析](/docs/computer/LinuxEpoll原理解析.md)
- [Socket常见异常](/docs/computer/Socket常见异常.md)
- [TCP有限状态机](/docs/computer/TCP有限状态机.md)
- [计算机网络教材整理](/docs/computer/计算机网络教材整理.md)
- [HTTP2的艺术？](/docs/computer/HTTP2的艺术？.md)
- [HTTPS实践](/docs/computer/HTTPS实践.md)
- [当你输入一个网址的时候，实际会发生什么?](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484257&idx=1&sn=e7704f92a1008ab7a292e2826bd079aa&chksm=fba6eb62ccd1627451d439bbc21e46e6fc1d7bfbe2a431fd887cf974a7bd0d9d482697f0e4fd&mpshare=1&scene=1&srcid=0608mcZB6SlZ2JGY46F7giS3%23rd)
- [BIO\NIO\Epoll\IO复用](BIO\NIO\Epoll\IO复用.md)

### 计算机是怎么跑起来的
- [计算机是怎么跑起来的](/docs/computer/计算机是怎么跑起来的.md)

### 开源框架
- [spring](/docs/framework/spring.md)
- [spring boot](/docs/framework/springboot.md)
- [SpringSecurity](/docs/framework/SpringSecurity.md)
- [spring cloud netflix](/docs/framework/springcloudnetflix.md)
- [spring cloud alibaba](/docs/framework/springcloudalibaba.md)
- [netty](/docs/framework/netty.md)
- [zookeeper](/docs/framework/zookeeper.md)
- [elasticsearch](/docs/framework/elasticsearch.md)
- [消息中间件](/docs/framework/消息中间件.md)
- [Guava](/docs/framework/Guava.md)
### 技术方案
- [DDD领域驱动](/docs/programme/DDD领域驱动.md)
- [异地多活](/docs/programme/异地多活.md)
- [网关](/docs/programme/网关.md)
- [高并发与高可用](/docs/programme/高并发与高可用.md)
- [链路追踪](/docs/programme/链路追踪.md)
- [秒杀架构](/docs/programme/秒杀架构.md)
### 数据库
- [mysql](/docs/db/mysql.md)
- [redis](/docs/db/redis.md)
### 微服务
- [分布式服务治理](/docs/springcloud/分布式服务治理.md)
- [分布式服务架构](/docs/springcloud/分布式服务架构.md)    
### 系统设计
   
### 内功心法
- [软件设计原则](/docs/dataStructure/软件设计原则.md)
- [设计模式](/docs/dataStructure/设计模式.md)  
- [算法与数据结构](/docs/dataStructure/算法与数据结构.md)
### 日常摘录及问题总结
- [软件设计原则](/docs/springcloud/分布式服务架构.md)
- [设计模式](/docs/springcloud/分布式服务架构.mdd)  
- [算法与数据结构](/docs/springcloud/分布式服务架构.md) 
### DevOps  
- [git](/docs/devOps/git.md)
- [maven](/docs/devOps/maven.md)  
- [docker](/docs/devOps/docker.md) 
### [面试专栏](/docs/Interview/interview.md)
  - [石杉面试突击第一季](#石杉面试突击第一季)
  - [石杉面试突击第二季](#石杉面试突击第二季)
  - [石杉面试突击第三季](#石杉面试突击第三季)

