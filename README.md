// zookeeper  server starts command
//go to window folder *(C:\Windows\System32\cmd.exe)
zookeeper-server-start.bat D:\kafka\kafka\config\zookeeper.properties

//kafka sever cammand
kafka to version 2.8.1.
kafka-server-start.bat D:\kafka\kafka\config\server.properties

Create Topic:
C:\kafka\bin\windows>kafka-topics.bat --create --topic tutorialspedia --bootstrap-server localhost:9092

Produce a message
D:\kafka\kafka\bin\windows>kafka-console-producer.bat --topic tutorialspedia --bootstrap-server localhost:9092 
 control+C then y

Consume a message
D:\kafka\kafka\bin\windows>kafka-console-consumer.bat --topic tutorialspedia --bootstrap-server localhost:9092


D:\kafka\kafka\bin\windows>kafka-console-consumer.bat --topic tutorialspedia --from-beginning --bootstrap-server localhost:9092
kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic javatechie


kafka-console-consumer.bat --topic javaJsonGuide --from-beginning --bootstrap-server localhost:9092
kafka-console-consumer.bat --topic wikimedia_new --from-beginning --bootstrap-server localhost:9092

Video Refrence Link :- https://www.youtube.com/playlist?list=PLGRDMO4rOGcNLwoack4ZiTyewUcF6y6BU
