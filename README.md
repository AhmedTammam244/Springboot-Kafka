# Spring Boot with Kafka Example

This Project covers how to use Spring Boot with Spring Kafka to Consume JSON/String message from Kafka topics
## Start Zookeeper
- `bin/zookeeper-server-start.sh config/zookeeper.properties`

## Start Kafka Server
- `bin/kafka-server-start.sh config/server.properties`

## Create Kafka Topic
- `bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example`
- `bin/kafka-topics.sh --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic Kafka_Example_json`


## Publish message via WebService
- `http://localhost:8081/kafka/Ahmed`
- `http://localhost:8081/kafka/Peter`
- `http://localhost:8081/kafka/Ali`
- `http://localhost:8081/kafka/Alaa`
- `http://localhost:8081/kafka/Saly`
- `http://localhost:8081/kafka/MEmy`