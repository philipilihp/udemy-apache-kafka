# udemy-apache-kafka
Code for the Udemy Course 'Apache Kafka Series - Learn Apache Kafka for Beginners v2'

Run container with Kafka Broker & Zookeeper:

```
docker run -p 2181:2181 -p 9092:9092 --env ADVERTISED_HOST=`docker-machine ip \`docker-machine active\`` --env ADVERTISED_PORT=9092 spotify/kafka
```
