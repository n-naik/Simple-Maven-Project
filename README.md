# Simple Maven Project

This is a simple Maven project that demonstrates the basic structure and functionality of a Java application.

## Project Structure

```
simple-maven-project
├── src
│   ├── main
│   │   └── java
│   │       └── App.java
│   └── test
│       └── java
│           └── AppTest.java
├── pom.xml
└── README.md
```

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Maven installed on your machine.

## Building the Project

To build the project, navigate to the project directory and run the following command:

```
mvn clean install
```

## Running the Application

After building the project, you can run the application using the following command:

```
java -cp target/simple-maven-project-1.0-SNAPSHOT.jar App
```

## Running Tests

To run the tests, use the following command:

```
mvn test
```

## License

This project is licensed under the MIT License.
