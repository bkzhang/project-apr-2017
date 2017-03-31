## Backend (Java SprintBoot version)

The Backend project serves REST API to the Frontend in order to provide the following functionality:

- Retrieve data needed to render a visualization.
- Retrieve the schema for a visualization.
- Retrieve the schema for a dashboard.
- Upload data which can be used for a visualization.
- And more

### Get Started

In order to get start, you will need to install the following tool.

1. [Java 8 (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) for the platform of your choice.
2. Lastest [Maven](https://maven.apache.org/download.cgi). Download, unzip, and add /bin to your PATH env var.

To compile the code:

`mvn clean compile`

To run tests:

`mvn test`

To run the webserver:

`mvn spring-boot:run`

To verify that your webserver started correct, browse to `http://localhost:8080/hello`.