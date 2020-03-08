# FlinkLearning

https://github.com/flink-china/flink-training-course 学习笔记  

### 戴资力
Stateful Stream Processor（有状态流式处理）  
global consistent snapshot（全局一致的快照）  
Checkpoint（检查点）  
Distributed Snapshots（分散式快照/分布式快照）  
checkpoint barrier  
Event Time  
Ingestion Time  
Window Processing Time  
Watermarks  
Savepoint（保存点）  

### 沙晟阳
standalone 单机模式、standalone 集群模式、YARN 集群模式  
Source/map() -> keyBy()/window()/apply() -> Sink  
JobManager/TaskManager  
HA 模式：主要是针对 JobManager(leader/standby)  

### 崔星灿
DataSteam API 编程  

### 周凯波（宝牛）
[凯波博客](https://zhoukaibo.com/)  
客户端操作，主要有以下五种：  
1. Command Line  
2. SQL Client  
3. Scala Shell  
4. Restful API  
5. Web  

### 邱从贤
Window & Time  

### 孙梦瑶
状态管理与容错机制  
如果数据源不支持重发，checkpoint 就没有意义了。

### 程鹤群（军长）
Table API 编程  
可以把 Table API 看作是 SQL 的超集，在易用性和功能性有增强  

### 云邪
SQL 编程  
Window Aggregate  
1. tumble window  
2. hop window  
3. session window  
Group Aggregate  

> 是非成败转头空  
> 青山依旧在  
> 几度夕阳红  
