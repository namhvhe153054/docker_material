# docker-kafka

## Quick Start

To deploy an example HDFS cluster, run:
```
  docker-compose up -d
```

## Access container kafka
```
  docker exec -it IDCONTAINER /bin/bash
```

### Producer send message to topic
```
  kafka-console-producer.sh --broker-list kafka:9092 --topic test
```

### Producer send message to topic
```
  kafka-console-consumer.sh --bootstrap-server kafka:9092 --topic test --from-beginning
```
