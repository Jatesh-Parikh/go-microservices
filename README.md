# gRPC Microservices Project with GraphQL API

This project demonstrates a microservices architecture using gRPC for inter-service communication and GraphQL as the API gateway. It includes services for account management, product catalog, and order processing.

> This project is based on a tutorial by [Akhil Sharma](https://www.youtube.com/watch?v=5UIh1dV7aZ8&list=PLHsjm_W8kcWZLPDxUplr8yredk95F-KIx).

## Project Structure

The project consists of the following main components:

- Account Service
- Catalog Service
- Order Service
- GraphQL API Gateway

Each service has its own database:
- Account and Order services use PostgreSQL
- Catalog service uses Elasticsearch