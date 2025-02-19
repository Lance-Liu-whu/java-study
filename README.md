# 目录

- [多线程](#多线程)

- [设计模式](#设计模式)

- [Spring](#Spring)

- [Java知识点整理](#Java知识点整理)

- [SpringBoot](#SpringBoot)

- [SpringCloud](#SpringCloud)

- [Docker](#Docker)

- [Dubbo](#Dubbo)

- [MQ](#MQ)
  
- [Mybatis](#Mybatis)
  
- [安装教程](#安装教程)

- [JVM](#JVM)
- [NIO](#NIO)

- **运维**

  - [Linux常用命令和操作](shell/Linux常用命令和操作.md)


- **其他**

    - [过vm检测](过vm检测.md)
    - [TP50以及TP99理解](TP50以及TP99理解.md)
    - [MyPerf4J结合Grafana和InfluxDB采集JVM以及QPS指标](MyPerf4J结合Grafana和InfluxDB采集JVM以及QPS指标.md)
    - [CentOS7环境下,Grafana9结合Prometheus,node_exporter,mysqld_exporter监控平台搭建](CentOS7环境下,Grafana9结合Prometheus,node_exporter,mysqld_exporter监控平台搭建.md)


- [汇编](#汇编)
- [Python](#python) 
- [计算机基础](#计算机基础) 


联系作者:

:imp: Q:920447939
:dog: [微信](md-file/wechat.jpg)
:cow: [点击加入Q群](https://jq.qq.com/?_wv=1027&k=5OvlqGh)





## **<a id="多线程">多线程</a>**
:sunny: [java 死锁的一个例子](java-bases/src/main/java/cn/withme/thread/DealLock.java)

:umbrella: [volatile测试](java-bases/src/main/java/cn/withme/myvolatile/VolatileTest01.java)

:cloud: [停止线程的方式](java-bases/src/main/java/cn/withme/thread/StopThreadUnsafe.java)

:snowflake: [锁住同一个对象就能保证多线程问题吗?](MulitThread.MD/#t1)

:zap: ​[测试SimpleDateFormat多线程发生异常](java-bases/src/main/java/cn/withme/date/ParseDate.java)







## **<a id="设计模式">设计模式</a>**
1. [~~策略模式~~](java-bases/src/main/java/cn/withme/pattern/StrategyPattern.java)

2. [~~工厂模式和抽象工厂模式~~](https://blog.csdn.net/qq920447939/article/details/104009055)

   

   

#### [重学设计模式](#重学设计模式)

## **<a id="Spring">Spring</a>**

1. [spring](./spring/README.md)
2. [通过BeanFactoryPostProcessor动态注入](./spring/README.md#t1)

3. [使用加密的属性文件](./spring/README.md#t2)




## **<a id="Java知识点整理">Java知识点整理(思维导图)</a>**
1. [Java知识点整理](./Java知识点整理.xmind)


## **<a id="SpringBoot">SpringBoot</a>**
1. [简单的spring boot  security 实现](./spring-boot/spring-boot-security)
2. [java SPI](spring-boot/spring-boot-java-spi/src/main/java/cn/withmes/spi/SpiTest.java)
3. [Spring boot session Redis简单实现](SpringBoot.MD/#t1)
4. [Spring boot JWT 实现](SpringBoot.MD/#t2)
5. [纯手写SpringBoot+Spring MVC](spring-boot/spring-boot-custom)
6. [SpringBoot实现自定义包扫描](./SpringBoot实现自定义包扫描.md)
7. [SpringBoot实现自定义start](./SpringBoot实现自定义start.md)
8. [SpringBoot适配异步Log4j](./SpringBoot适配异步Log4j.md)
9. [初探SpringBoot源码](./spring-boot源码探索)
10. [springboot log4j2 日志脱敏](./springboot_log4j2_日志脱敏.md)

## **<a id="SpringCloud">SpringCloud</a>**
1. [eureka服务注册与服务发现 + feign](spring-cloud/spring-cloud-eureka)
2. [ribbon源码研究](spring-cloud/spring-cloud-simulate-ribbon-service/src/main/java/cn/withmes/spring/cloud/simulate/ribbon/service/SimulateApplication.java)
3. feign源码研究
   1. [feignclient+Hystrix](spring-cloud/spring-cloud-fegin/spring-cloud-open-fegin-client/src/main/java/cn/withmes/springcloud/open/fegin/client/FeginClient.java)
   2. [feignserver+rabbion](spring-cloud/spring-cloud-fegin/spring-cloud-open-fegin-server/src/main/java/cn/withmes/spring/cloud/open/fegin/server/FeginServer.java)
   
4. SpringCloud集成 Eureka +Feign+ [Hystrix](https://github.com/Netflix/Hystrix)    
   - [测试以及配置链接](SpringCloud.MD/#t1)





## **<a id="Docker">Docker</a>**

1. [将spring-cloud项目打包成docker镜像并启动](Docker.MD/#t1)

2. [安装`docker-compose`(linux)](Docker.MD/#t2)

3. [使用docker-compose 进行服务编排](Docker.MD/#t3)

4. [使用`docker-compose` 同时部署多个docker 应用](Docker.MD/#t4)



## **<a id="Dubbo">Dubbo</a>**
1. 调用图 TODO

2. [错误分析](Dubbo.MD/#t2)
3. [基于Dubbo,本地Mock方案](基于Dubbo,本地Mock方案.md)
4. [源码分析(基于版本`2.5.x`)](Dubbo.MD/#t3)

- ​	dubbo 获取zk注册信息

## **<a id="MQ">MQ</a>**
1. [rabbitMQ部署方案以及生产消费demo](rabbitMQ.md)

## **<a id="Mybatis">Mybatis</a>**
1. [mybatis源码分析](mybatis源码分析/README.md)


  ## **<a id="安装教程">安装教程</a>**
1. [centOS离线安装nginx](install_tutorial/centos_offline_nginx_script.md)



## **<a id="重学设计模式">重学设计模式</a>**

1. [策略模式](https://blog.csdn.net/qq920447939/article/details/106985808)

## **<a id="汇编">汇编</a>**
1.[汇编指令通用寄存位宽](./assembler/汇编指令通用寄存位宽.md)

2.[汇编操作指令](./assembler/汇编操作指令.md)

3.[内存](./assembler/内存.md)

4.堆栈图

5.[C语言加法逆向](./assembler/C语言加法逆向.xlsx)


6.[StackDemo](./assembler/StackDemo.xlsx)


7.[vs学习](./assembler/vs学习.md)

8.[C++中的引用学习](./assembler/C++中的引用学习.md)


9.[给飞鸽传书增加一个节](./assembler/给飞鸽传书增加一个节.md)

10.[飞鸽传书在启动时弹一个信息框](./assembler/飞鸽传书在启动时弹一个信息框.md)

11.[PE文件结构1](./assembler/PE文件结构.md)

1. ​	[打印PE结构](./assembler/打印PE结构信息.md)


12.[PE文件结构网页版](./assembler/pe/index.HTM)

## **<a id="python">python</a>**
1.[win7安装anaconda并且pycharm使用anaconda](./python/win7安装anaconda并且pycharm使用anaconda.md)


## **<a id="JVM">JVM</a>**
1.[（1）深入理解Java虚拟机-内存模型](./JVM/（1）深入理解Java虚拟机-内存模型.MD)

2.[（2）深入理解Java虚拟机-内存溢出](./JVM/（2）深入理解Java虚拟机-内存溢出.MD)

3.[（3）深入理解Java虚拟机-GC如何判断对象可以回收](./JVM/（3）深入理解Java虚拟机-GC如何判断对象可以回收.MD)

4.[（4）深入理解Java虚拟机-GC的收集算法概念](./JVM/（4）深入理解Java虚拟机-GC的收集算法概念.MD)

5.[（5）深入理解Java虚拟机-对象的生命周期](./JVM/（5）深入理解Java虚拟机-对象的生命周期.MD)

6.[（6）深入理解Java虚拟机-类加载器](./JVM/（（6）深入理解Java虚拟机-类加载器.MD)

## **<a id="NIO">NIO</a>**
1.[NIO学习(IO模型)](./NIO学习(IO模型).md)

2.[NIO学习(reactor模型客户端与服务端)](./NIO学习(reactor模型客户端与服务端).md)

3.[Netty-概念](./Netty-概念.md)

4.[Netty-简单客户端与服务端通讯](./Netty-简单客户端与服务端通讯.md)


5.[Netty-粘包问题与自定义编码器](./Netty-粘包问题与自定义编码器.md)

6.[Netty简易HttpEcho服务器](netty-model/netty-echo-http/Netty简易HttpEcho服务器.md)





## **<a id="计算机基础">计算机基础</a>**

1. [对称加密和非对称加密](./计算机原理/对称加密和非对称加密.md)
2. [数字签名和数字证书](./计算机原理/数字签名和数字证书.md)

