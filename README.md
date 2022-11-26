### Spring Boot and Apache Kafka App

Order service produces and sends order events, while stock and email services consumes these events.

**Run Zookeeper and Kafka**

```bash
cd path\to\kafka

# Start the ZooKeeper service
bin\windows\zookeeper-server-start.bat config\zookeeper.properties

# Start the Kafka broker service
bin\windows\kafka-server-start.bar config\server.properties
```

**Build**

```bash
cd path\to\project_root
mvn clean install
```