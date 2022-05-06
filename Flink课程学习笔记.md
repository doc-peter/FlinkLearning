# FlinkLearning

[Flink 学习课程列表](https://github.com/flink-china/flink-training-course)

***学习建议***
1. **先实践再理论**。先学习应⽤，尝试构建复杂的Flink Application；
2. **横向扩展**。在构建复杂Flink⽣产业务后，横向使⽤学习Storm、Spark、DataFlow等系统，知识是演化过来的，必有前置和铺垫。多横向看看，打开视野；
3. 关注下Apache Flink以及Flink China社区，多交流、多提问、**多输出**。

## 陈守元（巴真）：为什么要学习 Apache Flink？
* Streams 流
  * bounded streams: 有始有终，不管计算多慢，一定会产生一个确定的结果
  * unbounded streams: 有始无终
* Time 时间
  * Event Time 事件时间
  * Processing Time 处理时间
  * Ingestion Time 注入时间
* Flink 适用场景
  * 实时数仓
  * 实时报表/大屏
  * 风控
* [Big Data 知识图谱](https://www.xmind.net/m/6fk4/)

## 戴资力：Flink基本概念（重点学习）
* Stateful Stream Processor（有状态流式处理）  
* global consistent snapshot（全局一致的快照）  
* Checkpoint（检查点）  
* Distributed Snapshots（分散式快照/分布式快照）  
* checkpoint barrier  
* Event Time  
* Ingestion Time  
* Window Processing Time  
* Watermarks  
* Savepoint（保存点）  

## 沙晟阳：Flink 安装部署、环境配置及运行应用程序
* 单机 standalone 模式、多机standalone 模式、YARN 集群模式  
* Source/map() -> keyBy()/window()/apply() -> Sink  
* JobManager/TaskManager  
* HA 模式：主要是针对 JobManager(leader/standby)  

## 崔星灿：DataStream API编程
* DataSteam API 编程  

## 周凯波（宝牛）：客户端操作
[凯波博客](https://zhoukaibo.com/)  
客户端操作，主要有以下五种：  
1. Command Line  
2. SQL Client  
3. Scala Shell  
4. Restful API  
5. Web  

## 邱从贤：Window & Time
Window & Time  

## 孙梦瑶：状态管理与容错机制
状态管理与容错机制  
如果数据源不支持重发，checkpoint 就没有意义了。

## 程鹤群（军长）：Flink Table API 编程
Table API 编程：可以把 Table API 看作是 SQL 的超集，在易用性和功能性有增强  

## 云邪：Flink SQL 编程
[云邪博客](http://wuchong.me/)  
SQL 编程  
Window Aggregation  
1. tumble window  
2. hop window  
3. session window  

Group Aggregation  

---

TO LEARN:
## 李康：Flink 作业问题分析和调优实践
## 崔星灿：Flink Time 深度解析
## 唐云：Flink Checkpoint-轻量级分布式快照
## 马庆祥：Flink 数据类型与序列化
## 唐云：Flink State 最佳实践
* [为什么要管理状态？](https://zhuanlan.zhihu.com/p/104171679)

---

> 是非成败转头空  
> 青山依旧在  
> 几度夕阳红  
