# CashCard

## Description

A REST API built with Spring Boot to manage "Cash Cards" — prepaid debit cards used as a controlled allowance for a family's children. The project was built following the **"Building a REST API with Spring Boot"** course from Spring Academy, guided by TDD (Test-Driven Development).

## Overview

The project simulates the backend of a system where parents register and manage Cash Cards for their children, each one holding a balance (`amount`). The application evolves progressively throughout the course, starting from a simple CRUD and later incorporating authentication and authorization, ensuring that each user can only access their own cards.

## Topics

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![TDD](https://img.shields.io/badge/TDD-2496ED?style=for-the-badge&logo=testinglibrary&logoColor=white)

## Learning Objectives

- Build a REST API from scratch using Spring Boot.
- Apply TDD as a development methodology, writing tests before implementation.
- Understand and implement CRUD operations (Create, Read, Update, Delete) following REST best practices.
- Work with JSON serialization/deserialization tests using `JacksonTester`.
- Implement pagination and sorting for resources.
- Add authentication and authorization with Spring Security, restricting each user's access to their own resources.
- Write integration tests with `@SpringBootTest` and `TestRestTemplate`.

## Repository Structure

```
CashCard/
├── src/
│   ├── main/
│   │   ├── java/example/cashcard/
│   │   │   ├── CashCard.java
│   │   │   ├── CashCardController.java
│   │   │   ├── CashCardRepository.java
│   │   │   └── CashCardApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── test/
│       ├── java/example/cashcard/
│       │   ├── CashCardJsonTest.java
│       │   └── CashCardApplicationTests.java
│       └── resources/
│           └── example/cashcard/
│               └── expected.json
├── build.gradle
├── settings.gradle
└── README.md
```

## References

- [Spring Academy — Building a REST API with Spring Boot](https://spring.academy/courses/building-a-rest-api-with-spring-boot)
- [Spring Boot Documentation](https://docs.spring.io/spring-boot/index.html)
- [AssertJ Documentation](https://assertj.github.io/doc/)

## License

MIT License
