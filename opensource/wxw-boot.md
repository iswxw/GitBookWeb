---
description: 基于springboot和springcloud系列的应用实践
---

以Java语言为主的各种项目实践，涵盖各个业务、各个功能


- github地址：https://github.com/iswxw/wxw-boot
- https://github.com/iswxw/springcloud2020
  

## 前言

现在市面上关于Java的教程和技术文章很多，其中有许多文章一上来就讲底层原理，这无疑给一些新手在理解上增加了难度，理解底层原理的前提是你的基本能力已经过关了。什么是基本能力呢？就是你能够使用这个技术去解决问题。

举一个较为极端的例子：现在很多关于MySQL文章都在讲解其底层原理，比如索引采用的B+树结构、事务是怎样实现的、千万级乃至上亿数据量怎么处理，等等，看完之后也了解相关知识了，但根据业务需求写一个复杂的SQL语句的时候就蒙圈了。

当我们去了解一个新框架、新组件、新技术时，第一步是了解其使用方法，在使用的过程中慢慢去了解其背后更深层次的原理，如果连一个技术的最佳实践都一无所知，又谈何深入理解呢？如果只知道理论却不去动手操作，那么很快就会忘记理论知识，我见过太多人在学习新技术时被那些“不接地气”的讲解给劝退了。

“知其所以然”的前提是“知其然”，为了弥补市面上“知其然”的空缺，我创建了【项目实践】这个系列。不谈那些“高大上”的东西，直接手把手教你实践，并且附上源码。让你在实践中掌握新的知识点，直观感受一项技术在实际项目中是如何运用的！然后再徐徐为你讲解技术背后的原理，让你真正做到“知其然”的同时轻松地“知其所以然”。

所有项目克隆下来即可运行，有部分项目质量甚至可以单独开一个仓库！点击star，我会不断更新更多项目实践的！


> 以项目驱动学习，以实践检验真知

## 项目实践系列

### 2.1 springboot系列

- [【项目实战】spring-dubbo](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-dubbo) 
- [【项目实战】spring-elasticsearch](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-elasticsearch)
- [【项目实战】spring-netty](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-netty) 
- [【项目实战】spring-redis](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-redis)      
- [【项目实战】spring-shiro](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-shiro)
- [【项目实战】spring-xxl-job](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-xxljob) 
- [【项目实战】spring-shardingsphere](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-shardingsphere)  
- [【项目实战】spring-rocketmq](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-rocketmq)  
- [【项目实战】spring-zookeeper](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-zookeeper) 
- [【项目实战】spring-mongodb](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-mongodb)
- [【项目实战】spring-quarts](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-quartz) 
- [【项目实战】spring-memcached](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-memcached) 
- [【项目实战】spring-rabbitmq](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-rabbitmq) 
- [【项目实战】spring-mybatis](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-mybatis)  
- [【项目实战】spriing-kafka](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-kafka) 
- [【项目实战】spring-junit](https://github.com/GitHubWxw/wxw-springboot/tree/dev-wxw/spring-junit)   
- [【项目实战】spring-shell](https://github.com/GitHubWxw/wxw-springboot/tree/dev-wxw/spring-shell)    
- [【项目实战】spring-batch](https://github.com/GitHubWxw/wxw-springboot/tree/dev-wxw/spring-batch) 
- [【项目实战】spring-prometheus-grafana](https://github.com/GitHubWxw/wxw-boot/tree/dev-wxw/spring-prometheus-grafana) 
- [【项目实战】spring-sentry](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-sentry) 
- [【项目实战】spring-configuration](https://github.com/iswxw/wxw-boot/tree/dev-wxw/spring-configuration) 

### 2.2 springcloud系列

> SpringCloud 生态

- [【项目实战 Spring Cloud  Gataway】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-gateway-server9527)   
- [【项目实战 Spring Cloud  Hystrix】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-hystrix-pay8001)      
- [【项目实战 Spring Cloud OpenFeign】]() 
- [【项目实战 Spring Cloud sleuth】]()  分布式请求链路跟踪
-  [【项目实战 Spring Cloud stream】]()  消息驱动 ，屏蔽底层 mq实现方式，统一消息编程模型 ，解决重复消费（使用消息分组解决）和持久化问题
- [【项目实战 Spring Cloud  bus】]()  服务配置总线
- [【项目实战 Spring Cloud  config】]()  服务集群配置中心 

> 服务注册与发现

- [【项目实战 Spring Cloud  Zookeeper】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-serverzk-pay8004)   
- [【项目实战 Spring Cloud  Consul 】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-consul-order8005) 
- [【项目实战 Spring Cloud  Eureka】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-server-eureka7001)   
- [【项目实战 Spring Cloud  Nacos】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-alibaba/cloud-nacos-order8001)   

>  SpringCloud Alibaba系列

- [【项目实战 Spring Cloud  nacos】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-alibaba/cloud-nacos-config-client3377)    
- [【项目实战 Spring Cloud  alibaba-histrix】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-alibaba-hystrix) 
- [【项目实战 Spring Cloud  alibaba-seata】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-alibaba-seata)   
- [【项目实战 Spring Cloud  alibaba-sentinel】](https://github.com/iswxw/springcloud2020/tree/dev-wxw/cloud-alibaba/cloud-sentinel-service8401)    

欢迎使用和Star支持，如使用过程中碰到问题，可以提出Issue，我会尽力完善。