#FROM amazoncorretto:latest
FROM openjdk:8

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

# Build the project with ./mvnw package
RUN ./mvnw package

# Run with java -jar ./target/docker-example-1.1.3.jar
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
