# datasphere-integration 数据集成平台介绍
----------------------------------------------
DataSphere 数据集成平台是集数据采集、数据接入、数据交换、数据同步、数据总线于一体的大数据集成平台，让传统IT架构迅速迈入数据智能时代。DataSphere 是基于分布式数据网格的云原生架构，具有高可扩展性和高可靠性，可在上百台集群规模上弹性伸缩。DataSphere 数据集成平台支持几乎所有主流数据源，可适配各种结构化、半结构化、非结构化的外部数据源，具有超高速的数据集成能力。

## DataSphere功能介绍
----------------------------------------------
* 实现关系型数据库、消息总线、系统接口、文件系统、大数据平台等。
* 实现跨系统、跨平台、跨网域之间的数据混合连接、互联互通。
* 可在SQL数据库、NoSQL数据库和Hadoop大数据平台之间实时流转数据。
* 分布式集群部署，扩展性高，处理速度快，适合于实时交换共享场景。
* 可数据容错，平台故障后，可保持数据完整性和一致性。
* 开发部署成本低，拖拉拽构建实时应用，管理简便。



## DataSphere功能亮点
----------------------------------------------
* 完全基于大数据技术：可大规模分布式集群部署。
* 支持几乎所有数据源：关系型数据库，各类文件，大数据平台，物联网数据。
* 数据吞吐量高：支持不少于100TB/天的数据采集交换能力 。
* 高并发并行处理：单集群支持5000个以上的高并发数据交换任务。
* 共享交换速度快：单任务每秒完成至少20万条业务数据的实时采集能力。
* 兼容开放性：可部署在主流的操作系统之上，开发平台API 供外部系统调用。
* 云服务部署：可部署在云环境，以自服务的方式为数据共享交换的用户提供服务。

## 架构原理
----------------------------------------------
请阅读 [架构原理](https://github.com/datasphere-oss/datasphere-integration/blob/master/docs/architecture.md) 文档

## 快速入门
----------------------------------------------
请阅读  [快速入门](https://github.com/datasphere-oss/datasphere-integration/blob/master/QUICKSTART.md) 文档


## 数据源列表


| 数据端名称  | 数据源端 | 数据目标端  | 开源  |
|-------------|:------:|-----------|----------:|
| Oracle      |   √    |     √     |    √      |
| MSSQL       |   √    |     √     |    √      |
| PostgreSQL  |   √    |     √     |    √      |
| TiDB        |   √    |     √     |    √      |
| Hashdata    |   √    |     √     |    √      |
| Greenplum   |   √    |     √     |    √      |
| Clickhouse  |   √    |     √     |    √      |
| Apache Hive |   √    |     √     |    √      |
| Apache HAWQ |   √    |     √     |    √      |
| Apache HBase|   √    |     √     |    √      |
| Apache HDFS |   √    |     √     |    √      |
| Apache Kafka|   √    |     √     |    √      |
| Apache Spark|   √    |     √     |    √      |
| Apache Flink|   √    |     √     |    √      |
| MQTT        |   √    |     √     |    √      |
| JMS         |   √    |     √     |    √      |

数据源支持持续更新中...
