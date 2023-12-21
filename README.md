# Microservices Project

This project demonstrates a microservices architecture consisting of multiple services, including a car service, a client service, a gateway, and a Eureka service.

## Services

### Car Service

The Car Service is responsible for managing car-related data. It provides CRUD operations for creating, reading, updating, and deleting car information.

### Client Service

The Client Service handles client-related functionalities. It manages client data and provides APIs for managing client information, such as creating clients, retrieving client details, and updating client information.

### Gateway

The Gateway acts as an entry point to the microservices ecosystem. It routes incoming requests from clients to the appropriate service based on the specified endpoint.

### Eureka Service

The Eureka Service provides service discovery and registration capabilities using the Eureka framework. It enables the other services to register themselves and discover other services in the microservices architecture.

## Technologies Used

- Java
- Spring Boot
- Spring Cloud
- Eureka

## Prerequisites

Make sure you have the following installed:

- Java Development Kit (JDK)
- Maven
