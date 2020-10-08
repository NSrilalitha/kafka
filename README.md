# kafka

Apache Kafka - Messaging system. Developed in 2010. Apache Kafka is written in pure Java and also Kafka’s native API is java. We can say Kafka has better throughput, built-in partitioning, replication, and fault-tolerance which makes it a good solution for large-scale message processing applications.

Whenever we transfer the data from one application to another application, we need messaging system to tranfer the data. There are two messaging patterns avaiable in general - point to point and publish - subscribe messaging system.

Enables the communication between producers and Consumers using message based topics. It is a publish-subscribe messaging system. Highly used in distributed systems to ensure high availability, scalability and auto recovery. Its performance rate is high to the tune of 100,000 messages/second.

One of the best features of Kafka is, it is highly available and resilient to node failures and supports automatic recovery. This feature makes Apache Kafka ideal for communication and integration between components of large-scale data systems in real-world data systems. Here, messages persist even after being processed. They don’t get removed as consumers receive them.


Kafka offers Kafka Broker, Kafka Consumer, Kafka Producer.

Terms:
1. Kafka cluster -> If Kafka has more than one broker, that is what we call a Kafka cluster.
2. Kafka topic -> message container
3. Kafka Broker -> It is a node on Kafka cluster. It persists and replicates the data. This manages the storage of messages in topic(S).
4. Kafka Producer -> It pushes the data into message container called Kafka topic
5. Kafka Consumer -> It pulls the message from Kafka topic
6. Kafka Zookeeper -> To offer the brokers with metadata about the processes running in the system and to facilitate health checking and broker leadership election, Kafka uses Kafka zookeeper.

References:

https://medium.com/@patelharshali136/apache-kafka-tutorial-kafka-for-beginners-a58140cef84f

https://kafka-tutorials.confluent.io/

