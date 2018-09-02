# Canal

English | [简体中文🇨🇳](https://github.com/alibaba/canal/blob/master/README.md)

**Canal** is a high performance data synchronization system based on MySQL binary log. Canal is widely used in Alibaba group (including https://www.taobao.com) to provide reliable low latency incremental data pipeline.

**Canal Server** is capable of parsing MySQL binlog and subscribe to the data change, while **Canal Client** can be implemented to broadcast the change to anywhere, e.g. database and [Apache Kafka](https://kafka.apache.org/).

## ✨Features
1. Support all platforms.
2. Support fine-grained system monitoring, powered by [Prometheus](https://prometheus.io/).
3. Support parsing and subscription to MySQL binlog by different ways, e.g. by GTID.
4. Support high performance, real-time data synchronization. (See more at [Performance](https://github.com/alibaba/canal/wiki/Performance))
5. Both Canal Server and Canal Client support HA/Scalability, powered by [Apache ZooKeeper](https://zookeeper.apache.org/)

## Usage
### 🐳Docker

[Canal Server Docker QuickStart](https://github.com/alibaba/canal/wiki/Docker-QuickStart)

### Install from source code

[Canal Server QuickStart](https://github.com/alibaba/canal/wiki/QuickStart)

[Canal Client QuickStart](https://github.com/alibaba/canal/wiki/ClientExample)

## Contributing [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
We strongly hope more and more people can enjoy Canal and make it better. We welcome all contributions. 
