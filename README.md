# hello-world

A fresh **Spring Boot** Hello World application.

## Requirements

- Java 21+
- Maven 3.9+ (or use the bundled Maven)

## Build

```bash
mvn clean package
```

## Run

```bash
mvn spring-boot:run
```

The application starts on port `8080`. Once running, visit:

```bash
curl http://localhost:8080/
# Hello, World!
```

## Test

```bash
mvn test
```

## Project structure

```
src/
├── main/
│   ├── java/com/example/helloworld/
│   │   ├── HelloWorldApplication.java   # Spring Boot entry point
│   │   └── HelloController.java         # REST controller serving "Hello, World!"
│   └── resources/
│       └── application.properties
└── test/
    └── java/com/example/helloworld/
        ├── HelloWorldApplicationTests.java  # Context load test
        └── HelloControllerTest.java         # Endpoint test
```

Built with Spring Boot 3.4.2.
