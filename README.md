# springboot-apachekafka commands to run in Commandline

Start Apache Zookeeper-
C:\kafka_2.12-0.10.2.1>.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

Start Apache Kafka-
C:\kafka_2.12-0.10.2.1>.\bin\windows\kafka-server-start.bat .\config\server.properties

Also Start the consumer listening to the monthly_salary-
C:\kafka_2.12-0.10.2.1>.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic monthly_salary --from-beginning
