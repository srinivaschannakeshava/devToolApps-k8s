 kafka-topics --zookeeper zk-service-cp:2181 --list

 kafka-topics --zookeeper zk-service-cp:2181 --topic test.visibility.flow.completed --describe
 
 kafka-consumer-groups --bootstrap-server localhost:29092 --list

 kafka-consumer-groups --bootstrap-server localhost:29092 --group DEV_1 --describe