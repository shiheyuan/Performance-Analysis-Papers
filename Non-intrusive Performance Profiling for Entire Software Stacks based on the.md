非侵入式性能分析
网络协议栈
flow重建原理

分布式服务器协议栈性能

一个请求导致在不同机器上的子请求
并发服务

通过非结构化的日志输出分析软件栈性能

无需领域知识，构建系统模型

自动重建

现有定位性能异常与原因工具：

加代码统计信息

分析已有日志log

机器学习：无法理解潜在系统行为，找不到问题成因

静态code分析：无法理解不同成员的交互

本文：聚焦对象、交互操作、从属关系

对log模式匹配，每一个log事件是哪些对象引起的

 (1) extract from the log messages
the object identifiers; 

(2) associate each extracted object
identifier with an object type; 

(3) identify how each object type is related to the other object types with respect
to participating in the same event; 

(4) identify the specific
object instances that are involved in each event; and 

(5)
identify execution structure and hierarchy between objects. 

自动log