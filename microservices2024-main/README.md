# Microservices Card Game

A small **microservices-based web application** built with **Java Spring Boot** and a simple frontend.  
It demonstrates how to split an application into multiple services and connect them through an **API Gateway**.  
The stack also includes **Docker** for running all services together.

## Features
- **Gateway** service that routes API requests to the right microservice
- **Card Service** for card game logic and data
- **Resolver, Recorder, Ongoing** services (handle game events / state)
- **Frontend** built with React for user interface
- **Docker** setup to run all services together locally

## Tech Stack
- Java 17 + Spring Boot
- Maven
- Node.js + React
- Docker & Docker Compose
- API Gateway pattern

## Running Locally

### Prerequisites
- Java 17+
- Maven
- Node.js 18+
- Docker Desktop

### Backend
```bash
cd Gateway
mvn spring-boot:run
