# Microservices

- monolith architecture vs microservices architecture
- monolith architecture: all the code is in one place

- microservices architecture: code is broken up into smaller services amd each service is represent as a small application
- service is responsible for a specific task
- service can be developed, deployed, and scaled independently
- service can be written in a different language
- service can have its own database , CI/CD pipeline, team, monitoring, logging, security, versioning, testing
- service can communicate with each other using HTTP, gRPC, or message broker

## Monolith Architecture

- monolith architecture: all the code is in one place
- A monolith contains (Routes, Middlewares, Business Logic, Database Access

## Database management between services

- every service has its own database bt it's not always the case
- services can share the same database
