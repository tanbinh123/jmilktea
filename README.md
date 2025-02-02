# 简介
jmilktea 名称由来：jay milk tea，杰伦奶茶，相信周杰伦的粉丝都会熟悉这个味道。杰伦是音乐界的天才，但是技术上我们都不是天才，唯有努力，滴水穿石，积跬步、至千里。本仓库主要记录开发相关技术知识，微服务，中间件使用，设计模式，工具的使用，常见的问题和解决方案等，以使用和实战为主，都是在实际中抽离出来的，也包括一些个人笔记，方便以后快速查找。

# 目录
## spring  
[spring bean生命周期](https://github.com/jmilktea/jmilktea/blob/master/spring/spring%20bean%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.md)     
[spring session统计登录人数](https://github.com/jmilktea/jmilktea/blob/master/spring/SpringSession%E7%BB%9F%E8%AE%A1%E7%99%BB%E5%BD%95%E4%BA%BA%E6%95%B0.md)  
[spring容器初始化完成事件](https://github.com/jmilktea/jmilktea/blob/master/spring/spring%E5%AE%B9%E5%99%A8%E5%88%9D%E5%A7%8B%E5%AE%8C%E6%88%90%E4%BA%8B%E4%BB%B6.md)  

## spring boot/cloud
[spring cloud gateway + nacos](https://github.com/jmilktea/jmilktea/blob/master/spring%20cloud/gateway-nacos/readme.md)  
[spring cloud gateway filter](https://github.com/jmilktea/jmilktea/blob/master/spring%20cloud/gateway-filter/gateway%20filter.md)    
[eureka 原理/集群](https://github.com/jmilktea/jmilktea/blob/master/spring%20cloud/eureka-ha/eureka-ha.md)    
[feign](https://github.com/jmilktea/jmilktea/blob/master/spring%20cloud/feign/feign.md)    
[除了java-jar,还能这样运行你的springboot应用](https://github.com/jmilktea/jmilktea/blob/master/spring%20cloud/springboot%E5%8F%AF%E6%89%A7%E8%A1%8C%E7%A8%8B%E5%BA%8F.md)       

## webflux
[错误处理](https://github.com/jmilktea/jmilktea/blob/master/webflux/%E9%94%99%E8%AF%AF%E5%A4%84%E7%90%86.md)  
[日志追踪](https://github.com/jmilktea/jmilktea/blob/master/webflux/%E6%97%A5%E5%BF%97%E8%BF%BD%E8%B8%AA.md)   
[全局异常处理](https://github.com/jmilktea/jmilktea/blob/master/webflux/%E5%85%A8%E5%B1%80%E5%BC%82%E5%B8%B8%E5%A4%84%E7%90%86.md)  
[expand递归](https://github.com/jmilktea/jmilktea/blob/master/webflux/expand%E9%80%92%E5%BD%92.md)  
[swagger](https://github.com/jmilktea/jmilktea/blob/master/webflux/swagger.md)  
[debug](https://github.com/jmilktea/jmilktea/blob/master/webflux/debug.md)  
[map&flatMap](https://github.com/jmilktea/jmilktea/blob/master/webflux/map%E5%92%8CflatMap.md)  
[源码分析](https://github.com/jmilktea/jmilktea/blob/master/webflux/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90.md)  

## 中间件
[nacos集群](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/nacos-cluster/nacos%E9%9B%86%E7%BE%A4.md)  
[canal简介](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/canal/canal%E7%AE%80%E4%BB%8B.md)  
[canal quick start](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/canal/quick%20start.md)   
[canal server ha](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/canal/canal%20server%20ha.md)   
[kafka消费者重启消息重复消费](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/kafka/%E6%B6%88%E8%B4%B9%E8%80%85%E9%87%8D%E5%90%AF%E6%B6%88%E6%81%AF%E9%87%8D%E5%A4%8D%E6%B6%88%E8%B4%B9%E9%97%AE%E9%A2%98.md)   
[kafka错误日志问题](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/kafka/%E9%94%99%E8%AF%AF%E6%97%A5%E5%BF%97%E9%97%AE%E9%A2%98.md)      
[apache common pool2](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/apache%20common%20pool2.md)    
[熔断-hystrix](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/%E7%86%94%E6%96%AD/hystrix.md)  
[熔断-resilience4j](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/%E7%86%94%E6%96%AD/resilience4j.md)     
[熔断-sentinel](https://github.com/jmilktea/jmilktea/blob/master/%E4%B8%AD%E9%97%B4%E4%BB%B6/%E7%86%94%E6%96%AD/sentinel.md)     

## elasticsearch
[核心概念](https://github.com/jmilktea/jmilktea/blob/master/elasticsearch/elasticsearch%E6%A0%B8%E5%BF%83%E6%A6%82%E5%BF%B5.md)    
[倒排索引](https://github.com/jmilktea/jmilktea/blob/master/elasticsearch/%E5%80%92%E6%8E%92%E7%B4%A2%E5%BC%95.md)      
[es/kibana/集群/cerebro搭建](https://github.com/jmilktea/jmilktea/blob/master/elasticsearch/elasticsearch%E6%90%AD%E5%BB%BA.md)   
[分词](https://github.com/jmilktea/jmilktea/blob/master/elasticsearch/%E5%88%86%E8%AF%8D.md)   
[常用api](https://github.com/jmilktea/jmilktea/blob/master/elasticsearch/%E5%B8%B8%E7%94%A8api.md)   

## linux  
[基础命令](https://github.com/jmilktea/jmilktea/blob/master/linux/%E5%91%BD%E4%BB%A4.md)  
[实操](https://github.com/jmilktea/jmilktea/blob/master/linux/%E5%AE%9E%E6%93%8D.md)   
[系统](https://github.com/jmilktea/jmilktea/blob/master/linux/%E7%B3%BB%E7%BB%9F.md)   
[五种IO模型](https://github.com/jmilktea/jmilktea/blob/master/linux/%E4%BA%94%E7%A7%8DIO%E6%A8%A1%E5%9E%8B.md)  
[零复制](https://github.com/jmilktea/jmilktea/blob/master/linux/%E9%9B%B6%E5%A4%8D%E5%88%B6.md)  
[顺序IO](https://github.com/jmilktea/jmilktea/blob/master/linux/%E9%A1%BA%E5%BA%8FIO.md)  

## mybatis
[核心流程和对象](https://github.com/jmilktea/jmilktea/blob/master/mybatis/%E6%A0%B8%E5%BF%83%E6%B5%81%E7%A8%8B%E5%92%8C%E5%AF%B9%E8%B1%A1.md)  
[拦截器](https://github.com/jmilktea/jmilktea/blob/master/mybatis/%E6%8B%A6%E6%88%AA%E5%99%A8.md)    
[springboot是如何集成mybatis的](https://github.com/jmilktea/jmilktea/blob/master/mybatis/springboot%E9%9B%86%E6%88%90mybatis%E5%8E%9F%E7%90%86.md)     

## mysql
[锁](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E9%94%81.md)  
[数据库开发规范](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E6%95%B0%E6%8D%AE%E5%BA%93%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83.md)   
[mysql三种log](https://github.com/jmilktea/jmilktea/blob/master/mysql/mysql%E4%B8%89%E7%A7%8Dlog.md)   
[一条危险的update语句](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E4%B8%80%E6%9D%A1%E5%8D%B1%E9%99%A9%E7%9A%84update%E8%AF%AD%E5%8F%A5.md)   
[使用p6spy监控应用sql](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E4%BD%BF%E7%94%A8p6spy%E7%9B%91%E6%8E%A7%E5%BA%94%E7%94%A8sql.md)  
[这么分页查数据居然重复了](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E8%BF%99%E4%B9%88%E5%88%86%E9%A1%B5%E6%9F%A5%E6%95%B0%E6%8D%AE%E5%B1%85%E7%84%B6%E9%87%8D%E5%A4%8D%E4%BA%86.md)  
[MVCC原理](https://github.com/jmilktea/jmilktea/blob/master/mysql/MVCC%E5%8E%9F%E7%90%86.md)       
[深入理解索引](https://github.com/jmilktea/jmilktea/blob/master/mysql/%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3%E7%B4%A2%E5%BC%95.md)        
[sql到底慢在哪里](https://github.com/jmilktea/jmilktea/blob/master/mysql/sql%E5%88%B0%E5%BA%95%E6%85%A2%E5%9C%A8%E5%93%AA%E9%87%8C.md)   
[order by居然有bug?](https://github.com/jmilktea/jmilktea/blob/master/mysql/orderby%20bug.md)   

## 设计
[编程相关的概念](https://github.com/jmilktea/jmilktea/blob/master/%E8%AE%BE%E8%AE%A1/%E7%BC%96%E7%A8%8B%E7%9B%B8%E5%85%B3%E6%A6%82%E5%BF%B5.md)    
[分层设计](https://github.com/jmilktea/jmilktea/blob/master/%E5%85%B6%E5%AE%83/%E5%88%86%E5%B1%82%E8%AE%BE%E8%AE%A1.md)   
[mq多环境topic设计](https://github.com/jmilktea/jmilktea/blob/master/%E8%AE%BE%E8%AE%A1/mq%E5%A4%9A%E7%8E%AF%E5%A2%83topic%E8%AE%BE%E8%AE%A1.md)   
[解决多环境下微服务实例乱窜](https://github.com/jmilktea/jmilktea/blob/master/%E8%AE%BE%E8%AE%A1/%E8%A7%A3%E5%86%B3%E5%A4%9A%E7%8E%AF%E5%A2%83%E4%B8%8B%E5%BE%AE%E6%9C%8D%E5%8A%A1%E5%AE%9E%E4%BE%8B%E4%B9%B1%E7%AA%9C.md)  

## 代码片段
[InputStream转String](https://github.com/jmilktea/jmilktea/blob/master/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5/inputstream2string.md)  
[apache-csv](https://github.com/jmilktea/jmilktea/blob/master/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5/apache-csv.md)    
[文件压缩解压](https://github.com/jmilktea/jmilktea/blob/master/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5/%E6%96%87%E4%BB%B6%E5%8E%8B%E7%BC%A9%E8%A7%A3%E5%8E%8B.md)  

## 其它
[druid加密](https://github.com/jmilktea/jmilktea/blob/master/%E5%85%B6%E5%AE%83/druid%E5%AF%86%E7%A0%81%E5%8A%A0%E5%AF%86.md)  
[jasypt加密配置文件](https://github.com/jmilktea/jmilktea/blob/master/%E5%85%B6%E5%AE%83/jasypt.md)  
[ThreadLocal扩展](https://github.com/jmilktea/jmilktea/blob/master/%E5%85%B6%E5%AE%83/ThreadLocal%E6%89%A9%E5%B1%95.md)   
[单元测试启动加速](https://github.com/jmilktea/jmilktea/blob/master/%E5%85%B6%E5%AE%83/%E5%8D%95%E5%85%83%E6%B5%8B%E8%AF%95%E5%90%AF%E5%8A%A8%E5%8A%A0%E9%80%9F.md)  

## 工具
[arthas实践](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/arthas/%E5%AE%9E%E8%B7%B5.md)   
[arthas tunnel]  
[github仓库多人协作](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/git/github%E4%BB%93%E5%BA%93%E5%A4%9A%E4%BA%BA%E5%8D%8F%E4%BD%9C.pdf)  
[git分支管理](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/git/%E5%88%86%E6%94%AF%E7%AE%A1%E7%90%86.md)  
[git合并参数ff nf squash](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/git/%E5%90%88%E5%B9%B6%E5%8F%82%E6%95%B0%20--ff%20--nf%20--squash.md)   
[git stash](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/git/git%20stash.md)  
[git tag](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/git/git%20tag.md)  
[jmeter](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/jmeter/jmeter.md)  
[curl](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/curl/curl.md)  
[idea插件汇总](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/%E6%8F%92%E4%BB%B6.md)  
[p3c插件](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/p3c.md)  
[yapiupload插件](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/yapiupload.md)   
[jrebel](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/jrebel.md)   
[基于upsource进行code review](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/%E5%9F%BA%E4%BA%8Eupsource%E8%BF%9B%E8%A1%8Ccode%20review.md)   
[写一个idea插件通知你gitlab远端分支变更了](https://github.com/jmilktea/jmilktea/blob/master/%E5%B7%A5%E5%85%B7%E7%B1%BB/idea/%E5%86%99%E4%B8%80%E4%B8%AAidea%E6%8F%92%E4%BB%B6%E9%80%9A%E7%9F%A5%E4%BD%A0gitlab%E8%BF%9C%E7%AB%AF%E5%88%86%E6%94%AF%E5%8F%98%E6%9B%B4%E4%BA%86.md)   

## 算法
[使用TreeSet优化任务分配.md](https://github.com/jmilktea/jmilktea/blob/master/%E7%AE%97%E6%B3%95/%E4%BD%BF%E7%94%A8TreeSet%E4%BC%98%E5%8C%96%E4%BB%BB%E5%8A%A1%E5%88%86%E9%85%8D.md)   
[限流算法](https://github.com/jmilktea/jmilktea/blob/master/%E7%AE%97%E6%B3%95/%E9%99%90%E6%B5%81%E7%AE%97%E6%B3%95.md)   
[时间轮算法]     
[缓存淘汰算法]    
[一致性hash算法](https://github.com/jmilktea/jmilktea/blob/master/%E7%AE%97%E6%B3%95/%E4%B8%80%E8%87%B4%E6%80%A7hash%E7%AE%97%E6%B3%95.md)      
[比例分配算法](https://github.com/jmilktea/jmilktea/blob/master/%E7%AE%97%E6%B3%95/%E6%AF%94%E4%BE%8B%E5%88%86%E9%85%8D%E7%AE%97%E6%B3%95.md)    

## redis
[redis常用配置参数](https://github.com/jmilktea/jmilktea/blob/master/redis/redis%E5%B8%B8%E7%94%A8%E9%85%8D%E7%BD%AE%E5%8F%82%E6%95%B0.md)   
[resp协议](https://github.com/jmilktea/jmilktea/blob/master/redis/resp%E5%8D%8F%E8%AE%AE.md)  
[redis定时任务](https://github.com/jmilktea/jmilktea/blob/master/redis/redis%E5%AE%9A%E6%97%B6%E4%BB%BB%E5%8A%A1.md)   
[redis单机和集群搭建](https://github.com/jmilktea/jmilktea/blob/master/redis/redis%E5%8D%95%E6%9C%BA%E5%92%8C%E9%9B%86%E7%BE%A4%E6%90%AD%E5%BB%BA.md)  
[缓存和数据库一致性问题](https://github.com/jmilktea/jmilktea/blob/master/redis/%E7%BC%93%E5%AD%98%E5%92%8C%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%80%E8%87%B4%E6%80%A7%E9%97%AE%E9%A2%98.md)   
[分布式锁](https://github.com/jmilktea/jmilktea/blob/master/redis/%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81.md)   
[string类型底层SDS](https://github.com/jmilktea/jmilktea/blob/master/redis/string%E7%B1%BB%E5%9E%8B%E5%BA%95%E5%B1%82SDS.md)  
[redis geo地理空间](https://github.com/jmilktea/jmilktea/blob/master/redis/redis%20geo%E5%9C%B0%E7%90%86%E7%A9%BA%E9%97%B4.md)  
[zset](https://github.com/jmilktea/jmilktea/blob/master/redis/zset.md)   
[zset实践](https://github.com/jmilktea/jmilktea/blob/master/redis/zset%E5%AE%9E%E8%B7%B5.md)   
[hash](https://github.com/jmilktea/jmilktea/blob/master/redis/hash.md)  

## 基础  
[反射](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/%E5%8F%8D%E5%B0%84.md)  
[jvm常用参数](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/jvm%E5%B8%B8%E7%94%A8%E5%8F%82%E6%95%B0.md)    
[@Transactional不生效?](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/%40Transactional%E4%B8%8D%E7%94%9F%E6%95%88%EF%BC%9F.md)  
[java开发规范](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/java%E8%A7%84%E8%8C%83.md)   
[什么？@Transactional又不生效了？](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/%E4%BB%80%E4%B9%88%EF%BC%9F%40Transactional%E5%8F%88%E4%B8%8D%E7%94%9F%E6%95%88%E4%BA%86%EF%BC%9F.md)   
[cas](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/cas.md)   
[java集合类型-Queue继承体系](https://github.com/jmilktea/jmilktea/blob/master/%E5%9F%BA%E7%A1%80/%E9%9B%86%E5%90%88%E7%B1%BB%E5%9E%8B/Queue.md)    

## 问题总结   
[java cpu占用高问题排查](https://github.com/jmilktea/jmilktea/blob/master/%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88/java%E5%BA%94%E7%94%A8cpu100%25(%E5%90%ABdocker).md)  
[java 内存占用高问题排查](https://github.com/jmilktea/jmilktea/blob/master/%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88/java%E5%BA%94%E7%94%A8%E5%86%85%E5%AD%98%E5%8D%A0%E7%94%A8%E9%AB%98%E9%97%AE%E9%A2%98.md)  
[HttpClient线程池设置问题](https://github.com/jmilktea/jmilktea/blob/master/%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88/HttpClient%E7%BA%BF%E7%A8%8B%E6%B1%A0%E8%AE%BE%E7%BD%AE%E9%97%AE%E9%A2%98.md)  
[rm命令删除文件了,但磁盘空间没有释放](https://github.com/jmilktea/jmilktea/blob/master/%E9%97%AE%E9%A2%98%E6%80%BB%E7%BB%93/linux%E5%88%A0%E9%99%A4%E6%96%87%E4%BB%B6%E6%B2%A1%E6%9C%89%E9%87%8A%E6%94%BE%E7%A9%BA%E9%97%B4.md)   

## 面试  
[双亲委派机制](https://github.com/jmilktea/jmilktea/blob/master/%E9%9D%A2%E8%AF%95/%E5%8F%8C%E4%BA%B2%E5%A7%94%E6%B4%BE%E6%9C%BA%E5%88%B6.md)   
[jdk动态代理与cglib](https://github.com/jmilktea/jmilktea/blob/master/%E9%9D%A2%E8%AF%95/jdk%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E4%B8%8Ecglib.md)   
[tcp三次握手四次挥手](https://github.com/jmilktea/jmilktea/blob/master/%E9%9D%A2%E8%AF%95/tcp%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B.md)   
[CountDownLatch和CyclicBarrier](https://github.com/jmilktea/jmilktea/blob/master/%E9%9D%A2%E8%AF%95/CountDownLatch%E5%92%8CCyclicBarrier.md)  
