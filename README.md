# flink-
Flink1.10.0的入门自测

https://www.cnblogs.com/yaowentao/p/12317356.html

目的：已在CDH集群上已配置好Flink1.10.0， 
    1.学习如何提交flink任务，参数设置
    第一个例子：
    1）在hdfs上创建一个简单的word.txt,地址为hdfs://x.x.x.x:8020/tmp/word.txt
    2）在集群的一个flink-yarn上提交作业：flink run -m yarn-cluster -yn 4 -yjm 1024 -ytm 1024 /opt/cloudera/parcels/FLINK/lib/flink/examples/streaming/WordCount.jar --input hdfs://x.x.x.x:8020/tmp/word.txt --output hdfs://192.168.1.110:8020/tmp/result
    
    2.学习IDEA的flink-scala代码写法与相关依赖
    3.学习Flink的调优
