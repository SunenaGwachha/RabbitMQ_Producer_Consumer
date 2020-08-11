# RabbitMQ_Producer_Consumer

Getting Starting with RabbitMQ
In this post we will download and start RabbitMQ instance.
RabbitMQ is open source message broker software (sometimes called message-oriented middleware) that implements the Advanced Message Queuing Protocol (AMQP). The RabbitMQ server is written in the Erlang programming language and is built on the Open Telecom Platform framework for clustering and failover.

https://www.youtube.com/watch?v=h8b1dXgPulQ

https://www.javainuse.com/spring/spring-boot-rabbitmq-hello-world

Producer Code here
https://www.javainuse.com/misc/rabbitmq-hello-world

Consumer Code here
https://www.javainuse.com/spring/spring-boot-rabbitmq-consume
 


Since RabbitMQ is built on top of Erlang, we will first need to install Erlang. Got to the Erlang downloads page and download the erlang binary file for windows which is an executable.

•	Next run the binary file downloaded and install erlang on your machine.
•	Go to RabbitMQ downloads page and download RabbitMQ installation.
Lets Begin-
•	Since RabbitMQ is built on top of Erlang, we will first need to install Erlang. Got to the Erlang downloads page and download the erlang binary file for windows which is an executable.
 
•	Next run the binary file downloaded and install erlang on your machine.
•	Go to RabbitMQ downloads page and download RabbitMQ installation.
 
This will be a .exe installation file for windows.
•	Run this exe and install RabbitMQ on your machine.
•	We will now start Rabbit. The above installation should have installed the RabbitMQ command prompt. Open it.
Go to the RabbitMQ Server Location and use the command as follows-
•	rabbitmq-server start

 
If RabbitMQ already running we get the above message.
•	Next we will install the RabbitMQ plugin which will give use the RabbitMQ Management Console which is accessible using the browser. For this use the command as follows-
•	rabbitmq-plugins.bat enable rabbitmq_management

 
•	Next go to localhost:15672.We will see the RabbitMQ console. The default username and password is guest.
