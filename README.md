# Kafka-Node example

1) spin up Docker containers: `docker-compose up`

2) create kafka topic
`docker exec -it kafka /opt/bitnami/kafka/bin/kafka-topics.sh --create --topic test --bootstrap-server localhost:9092 --replication-factor 1 --partitions 1`