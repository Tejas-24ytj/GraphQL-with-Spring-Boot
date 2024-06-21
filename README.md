# GraphQL with Spring Boot

This project demonstrates how to set up a basic GraphQL server using Spring Boot. The server will be available on `http://localhost:8080/graphiql`.

![Screenshot 2024-06-21 213534](https://github.com/Tejas-24ytj/GraphQL-with-Spring-Boot/assets/105742352/a8d26ad6-6368-4514-b0e2-c00626f532a7)

![Screenshot 2024-06-21 190306](https://github.com/Tejas-24ytj/GraphQL-with-Spring-Boot/assets/105742352/a869c5b2-4333-44f6-8f90-562cbe62f6e0)

![Screenshot 2024-06-21 213643](https://github.com/Tejas-24ytj/GraphQL-with-Spring-Boot/assets/105742352/3661b98f-f410-44bb-a078-17ef2bdccbed)

![Screenshot 2024-06-21 190020](https://github.com/Tejas-24ytj/GraphQL-with-Spring-Boot/assets/105742352/e673501b-9714-44ab-93aa-f3682f45dd17)

![Screenshot 2024-06-21 190045](https://github.com/Tejas-24ytj/GraphQL-with-Spring-Boot/assets/105742352/c2ed68dd-06b0-455f-90d4-7a9198a6ef00)



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




  





