# GraphQL with Spring Boot

This project demonstrates how to set up a basic GraphQL server using Spring Boot. The server will be available on `http://localhost:8080/graphiql`.

## Prerequisites

- Java 17 or later
- Maven 3.6.0 or later

## Getting Started

### 1. Create a new Spring Boot project

Create a new Spring Boot project using Spring Initializr (https://start.spring.io/) with the following dependencies:
- Spring Web
- GraphQL

### 2. Configure GraphQL

Create a `schema.graphqls` file in `src/main/resources/graphql`:

```graphql
type Query {
    hello: String
}

### 3. Access the application

http://localhost:8080/graphiql to access the GraphiQL interface. 








  





