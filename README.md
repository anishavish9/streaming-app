
# Streaming Application

This project is a microservices-based streaming platform that provides a modular and scalable architecture for managing user authentication, movie recommendations, and gateway-level routing. Built using Spring Cloud, Eureka Server, and Spring Boot, the system leverages microservice patterns for efficient communication, load balancing, and dynamic service discovery.

## Tech Stack

**Server:** Eureka

**Backend:** Java, Spring Boot, Microservice, API Gateway, Security

**Database:** MySQL, MongoDB
## Run Locally

Clone the project

**Prerequisites:**
Ensure you have JDK (8+), Maven, MongoDB, Mysql, and optionally Postman installed.

```bash
  git clone https://github.com/anishavish9/streaming-app.git
```

Go to the project directory

```bash
    cd streaming-app
```

Run the following command in the project root:
Install dependencies

```bash
    mvn clean install
```

Run the Services:
Start each service in this order:

Eureka Server:
```bash
cd eureka-server
mvn spring-boot:run
```

API Gateway:
```bash
cd ../api-gateway
mvn spring-boot:run
```

User Authentication Service:
```bash
cd ../user-authentication-service
mvn spring-boot:run
```

User Movie Service:
```bash
cd ../user-movie-service
mvn spring-boot:run
```
## Support

For support, email anishavishwakarma60@gmail.com.

