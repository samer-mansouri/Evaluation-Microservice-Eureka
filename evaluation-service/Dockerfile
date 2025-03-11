FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/evaluation-service-0.0.1-SNAPSHOT.jar evaluation-service.jar

EXPOSE 8082

ENTRYPOINT ["java", "-jar", "evaluation-service.jar"]
