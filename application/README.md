# Todo Application for AWS 101

The purpose of this todo application is to serve as an example for the various use cases covered by the book.

## Getting Started

### Prerequisites

* [Java 11 or higher](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
* [Gradle](https://gradle.org/)

### Running the app in dev mode

Run ```gradle bootRun``` from the command line.

## Running the tests

Run ```gradle build``` from the command line.

## Deployment

You can run the application by using the standard Spring Boot deployment mechanism (see these three articles for more
information on Spring Boot deployment techniques and alternatives:
[Deploying Spring Boot Applications](https://spring.io/blog/2014/03/07/deploying-spring-boot-applications),
[Running your application](https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-running-your-application.html),
[Installing Spring Boot applications](https://docs.spring.io/spring-boot/docs/current/reference/html/deployment-install.html)):

```java -jar target/todo-application-0.0.1-SNAPSHOT.jar```

The application then should be available under [http://localhost:8080](http://localhost:8080)

## Built With

* [Spring Boot](https://projects.spring.io/spring-boot/)
* [Gradle](https://gradle.org/)

## License

[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

## Authors

* **[Tom Hombergs](https://reflectoring.io)**
* **[Philip Riecks](https://rieckpil.de)**
* **[Björn Wilmsmann](https://bjoernkw.com)**
