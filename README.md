# Sample server demonstrating Go working with ApapcheKafka

**Goal: Gain thorough theoritical and practical understanding of Apache Kafka**

* Complete the first Messaging example using Kafka.
* Setup Kafka in Kubernetes Kluster.
* Build and deploy three related potentially high activity Go services on the cluster.
----
* Total Time: 48 Hours
* 3 Hours to build first example
* 6 Hourse rest
* 5 Hours to setup Kafka in Kubernetes cluster.
* 34 Hours to build Related services.
----


**Setup kafka local Kafka cluster**
* To start the cluster run:

  -- `git clone https://github.com/wurstmeister/kafka-docker`

  -- `docker-compose up -d`

* To scale to more brokers run:

  -- `docker-compose scale kafka=3`

* To stop the cluster run:

  -- `docker-compose stop`