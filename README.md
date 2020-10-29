# Insurance Platform Upgrade
The project aims to develop a microservice-based platforms for insurance department. The goal is to provide insurance agents with intelligent insights across all channels, provide customers with easy available services and also provide manager with data visulization reports. The project is based on **Spring Boot 2.0**.

## Architecture

Our microservices-based system consists of the following modules:
- **gateway-service** - a module that Spring Cloud Netflix Zuul for running Spring Boot application that acts as a proxy/gateway in our architecture.
- **discovery-service** - a module that depending on the example it uses Spring Cloud Netflix Eureka as an embedded discovery server.
- **contact automation-service** - a module sends the customized requests by user to the backend and contact specific agents for user by doing CRUD operations to the database,
- **caller reward-service** - a module record the angents' performence by doing CRUD to the database and generate data visulization reports by D3.JS . It communicates with contact automation service. 


<img src="https://drive.google.com/file/d/1-5hTmjiQdiYnMYc0iV5uBSlN2JHiRUb1/view" title="Architecture"/>


## Environment
Java/Jdk 1.8, Spring Boot 2.0, Docker 18.09.5, AWS EC2, AWS S3, Spring Cloud, Redis 5.0.4, RabbitMQ 3.7.12, OAuth 2.0, Spring Security 5.0, JWT, Angular 8,  Bootstrap 4.2.1, HTML5, CSS3, jQuery 3.3, AJAX, Spring Tool Suite 3, Postman 6.7.4, JUnit 5.4.0, Mockito, Jenkins 2, Git, Maven 3

## Run with
mvn spring-boot : run
