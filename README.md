# queue-dock

基于 Docker Compose 搭建的消息队列服务环境

# IP地址

内部IP地址从 172.25.34.3 开始

## Queue (消息队列)
172.21.7.3 start

## Kafka Raft (172.21.7.3~172.21.7.4)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | kafka-kraft | 172.21.7.3 | 172.20.7.3 | 3.9 | |
| [&check;] | kafka-ui | 172.21.7.4 | 172.20.7.4 | latest | | |

## Kafka Zookeeper 模式 (172.21.7.5~172.21.7.8)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | kafka | 172.21.7.5 | 172.20.7.5 | 3.9 | |
| [&check;] | zookeeper | 172.21.7.6 | 172.20.7.6 | 3.9 | |
| [&check;] | kafka-ui | 172.21.7.7 | 172.20.7.7 | latest | | |
| [&check;] | zoonavigator | 172.21.7.8 | 172.20.7.8 | latest | | |

## Rabbitmq (172.21.7.11~172.21.7.11)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | rabbitmq | 172.21.7.11 | 172.20.7.11 | latest | | |

## Rocketmq (172.21.7.20~172.21.7.30)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&cross;] | rocketmq-dashboard | 172.21.7.20 | 172.20.7.20 | latest | | |
| [&cross;] | rocketmq-namesrv | 172.21.7.21 | 172.20.7.21 | latest | | |
| [&cross;] | rocketmq-broker | 172.21.7.22 | 172.20.7.22 | latest | | |

## Pulsar (172.21.7.31~172.21.7.35)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | pulsar | 172.21.7.31 | 172.20.7.31 | latest | | |
| [&check;] | pulsar-manager | 172.21.7.32 | 172.20.7.32 | latest | | |

## Nats (172.21.7.40~172.21.7.41)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | nats | 172.21.7.40 | 172.20.7.40 | latest | | |

## Beanstalkd (172.21.7.50~172.21.7.51)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&check;] | beanstalkd | 172.21.7.50 | 172.20.7.50 | latest | | |
| [&check;] | beanstalkd-console | 172.21.7.51 | 172.20.7.51 | latest | | |


# 使用到的镜像
```json
[
]
```
