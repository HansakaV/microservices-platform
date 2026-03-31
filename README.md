# Backend: Microservices Platform

This repository contains the core platform services for the Bus Depot Management System.

## Student Information
- **Name:** Mahesh Hansaka
- **Student Number:** 2301691104
- **GCP Project ID:** bus-depot-management-491905 

## Platform Services
1. **Config Server**: Centralized configuration management.
2. **Eureka Service Registry**: Service discovery and registration.
3. **API Gateway**: Single entry point for all client requests.

## Technology Stack
- Java 
- Spring Boot
- Spring Cloud (Gateway, Config, Netflix Eureka)

## Setup Instructions
1. Navigate to each service directory.
2. Build with `./mvnw clean install`.
3. Run using `java -jar target/[service-name]-0.0.1-SNAPSHOT.jar`.
