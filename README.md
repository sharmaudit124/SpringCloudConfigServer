# SpringCloudConfigServer

**Project:** Maven  
**Language:** Java  
**Group:** com.config  
**Artifact:** SpringCloudConfigServer  
**Name:** SpringCloudConfigServer  
**Description:** Demo project for Spring Boot Cloud Config server using MySQL JDBC  
**Package Name:** com.config.SpringCloudConfigServer  
**Packaging:** Jar  
**Java:** 17  

## Dependencies:

- Config Server
- Spring Data JDBC SQL
- Spring Web
- MySQL Driver

## Overview

SpringCloudConfigServer is a demo project that showcases the usage of Spring Boot Cloud Config server with MySQL JDBC as the backend data store. This project provides a centralized configuration management solution, allowing you to store and manage configuration properties for multiple microservices in a Git-backed MySQL database.

## Prerequisites

- Java Development Kit (JDK) 17
- Maven
- MySQL database

## Getting Started

1. Clone this repository to your local machine.
2. Configure your MySQL database and update the database connection details in the `application.properties` file.
3. Build the project using Maven:`mvn clean install`.
4. After building the project, you can run the Spring Boot application using the `java` command.
`java -jar target/your-application-name.jar`
