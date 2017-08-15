# hadoop-kafka
#### Purpose:
1) Read events from topic and return only of specified type  
2) Download URI (using cURL), apply specified function, return what function returns and clean downloaded files

#### In order to run the program

- run *sbt assembly*
- run jar with parameters (topic name to read from, kafka IP address, type of events to return), example:  
*java -jar hadoop-kafka-assembly-1.0.jar --topic TopicName --kafkaIpPort localhost:9092 --ofType AvailableForProcessing*