# Sample Event-Driven Microservice App Using Spring Cloud Stream

this repository, I have two Spring Boot applications that utilize the Spring Cloud Stream Apache Kafka messaging solution for event-driven microservices. I hope this example app will help you get started!

## Important

Before you get started, please ensure that you have installed Zookeeper and Apache Kafka on your system or via Docker. Please see the link below for a detailed explanation on how to achieve this:

### [How to Install Apache Kafka Using Docker — The Easy Way](https://example.com)

## Create a Broker

A broker is simply the machine (typically a VM) where your topics will reside. You'll need to create a broker and use the host and port number in the configuration of your producer and consumer applications. I configured mine in the `application.yml` file located in the resource folder of each microservice.

## Create Your Topic

A topic in Kafka is like a log file where all your events, once published, will be appended and can subsequently be consumed by a consumer application. Therefore, you will need to create a topic.

## Good to Go! 

You're all set to explore the event-driven architecture with Spring Cloud Stream and Kafka. Happy coding!
