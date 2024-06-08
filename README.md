# Test Spring Boot MVC Cloud Gateway Server

This project was used to demo some features of the [Spring Boot MVC Cloud Gateway Server](https://docs.spring.io/spring-cloud-gateway/reference/spring-cloud-gateway-server-mvc.html)

For now, this project just routes requests to the downstream [recetas-java](https://github.com/rhett-raleigh/recetas-java) Spring Boot REST API

## Getting Started

### Prerequisites

Java 21

The [recetas-java](https://github.com/rhett-raleigh/recetas-java) project checked out in a directory adjacent to this project's directory, with a valid build.

To build
`./gradlew build`

To run
`docker-compose up --build`

At this point you should be able to make a request to `GET http://localhost:8080/recipes` which will be fulfilled by the recetas-java API.
