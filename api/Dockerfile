FROM openjdk:17-jdk-slim
WORKDIR /app
COPY target/api.jar api.jar
EXPOSE 8080
ENTRYPOINT ["java", "-Dserver.port=8080", "-jar", "api.jar"]

