# Java Hello World Application

This project is a simple Java application that prints "Hello, World!" to the console. It is structured to demonstrate the use of Maven for building the project and Jenkins for continuous integration.

## Project Structure

```
java-hello-world
├── src
│   └── main
│       └── java
│           └── HelloWorld.java
├── Jenkinsfile
├── pom.xml
└── README.md
```

## Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Maven installed on your machine.
- Jenkins for continuous integration (optional).

## Building the Application

To build the application, navigate to the project directory and run the following command:

```
mvn clean install
```

This command will compile the Java code and package it into a JAR file.

## Running the Application

After building the application, you can run it using the following command:

```
java -cp target/java-hello-world-1.0-SNAPSHOT.jar HelloWorld
```

This command will execute the `HelloWorld` class and print "Hello, World!" to the console.

## Jenkins Pipeline

The `Jenkinsfile` in this project defines the pipeline for building, testing, and deploying the application. Make sure to configure your Jenkins server to use this file for continuous integration.

## License

This project is licensed under the MIT License.