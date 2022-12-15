# springboot-kafka-real-world-project
Sample project which explains about how to integrate Kafka using Springboot.

## Prerequisite

- Install JDK 8 or above in your system.
- Install MySQL server in you local machine.
- Install Apache Kafka latest version in your local machine.

## MySQL Password setup
### Run MySQL on terminal
mysql -u root -p

### Secure password via installations- Run below command in terminal(for MAC OS), it will ask few trivial questtions and just give answers accordingly and then reset password at last.
/usr/local/bin/mysql_secure_installation

## Apachhe Kafka Useful Commands

### Start the ZooKeeper service
$ bin/zookeeper-server-start.sh config/zookeeper.properties

## Start the Kafka broker service
$ bin/kafka-server-start.sh config/server.properties

## Read message from topic
$ bin/kafka-console-consumer.sh --topic topic1 --from-beginning --bootstrap-server localhost:9092
