# Microservices Starter Project

#### by Simbarashe Jerry Maunga

This repository contains a demo project demonstrating a microservices-based application. It is designed to provide practical insights into microservices architecture and implementation. The project includes an API Gateway, Config Server, Discovery Server, and two microservices: Student and School.

## Getting Started

Follow the instructions below to set up the project on your local machine for development and testing.

### Prerequisites

Ensure you have the following software installed on your system:

- Java Development Kit (JDK) 17 or later
- Maven
- Docker (optional, for containerization)

### Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Build and package each component with Maven:

## Project Components

### API Gateway

The API Gateway acts as the single entry point for all client requests, managing and routing them to the appropriate microservices.

### Config Server

The Config Server centralizes configuration management for all microservices, simplifying application maintenance and ensuring consistency across environments.

### Discovery Server

The Discovery Server provides service registration and discovery, enabling seamless service-to-service communication within the microservices ecosystem.

### Student Microservice

The Student Microservice handles student-related data and operations, such as adding, updating, and retrieving student records.

### School Microservice

The School Microservice manages school-related data and operations, including adding, updating, and retrieving school records.

## Inter-Service Communication

### Using OpenFeign

This project demonstrates inter-service communication using OpenFeign, a declarative REST client that simplifies service-to-service communication within the microservices ecosystem.

## Distributed Tracing

### Using Zipkin

The project showcases the use of Zipkin for distributed tracing, enhancing application observability and enabling the visualization and troubleshooting of latency issues.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

[Simbarashe Maunga]

[Website] - [https://mrscriptstudio.com]

Project Link: [https://github.com/Maunga/springboot-3-micro-service-starter](https://github.com/Maunga/springboot-3-micro-service-starter)

## Acknowledgements

- [OpenFeign](https://github.com/OpenFeign/feign)
- [Zipkin](https://zipkin.io/)
- [Spring Cloud Netflix](https://spring.io/projects/spring-cloud-netflix)
