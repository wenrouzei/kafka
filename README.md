# 本地kafka启动

## 启动zookeeper，添加`-daemo`参数以守护进程模式启动
`./bin/zookeeper-server-start.sh -daemon config/zookeeper.properties`

## 启动kafka
`./bin/kafka-server-start.sh -daemon config/server.properties`

## 如果启动失败，先删除日志记录
`rm -rf /tmp/kafka-logs/`

` rm -rf /tmp/zookeeper/`


