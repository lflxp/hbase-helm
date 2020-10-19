# Useage

准备条件：

1. kubernetes cluster
2. nfs storageClass default

命令:

> cd zookeeper
> helm install myzk .
> cd ../hbase-helm-yarn
> helm install bigdata .

# Version

* HDFS 2.7.3
* HBASE 1.3.1
* ZOOKEEPER 3.5.5

# Flume

数据采集工具

## 使用

> kubectl apply -f flume/flume.yaml

# Spark

> cd sparkoperator

> helm install spark -n spark-operator .

# TODO

* KAFKA
* FLINK
* Mysql
* Mongo
* Elasticsearch
* Redis
