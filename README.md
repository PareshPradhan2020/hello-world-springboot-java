# Hello World Spring Boot Application

This is a simple Spring Boot application that demonstrates a basic "Hello World" functionality.

## Prerequisites

- Java 11 or higher
- Maven

## Getting Started

1. Clone the repository:

   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```
   cd hello-world-springboot
   ```

3. Build the project using Maven:

   ```
   mvn clean install
   ```

4. Run the application:

   ```
   mvn spring-boot:run
   ```

5. Open your web browser and go to `http://localhost:8080` to see the "Hello World" message.

## Project Structure

```
hello-world-springboot
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── helloworld
│   │   │               └── HelloWorldApplication.java
│   │   └── resources
│   │       └── application.properties
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── helloworld
│                       └── HelloWorldApplicationTests.java
├── pom.xml
└── README.md
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.