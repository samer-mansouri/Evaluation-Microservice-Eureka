# Use OpenJDK image
FROM openjdk:17-jdk-slim

# Set working directory inside the container
WORKDIR /app

# Copy JAR file (Make sure to build the JAR first!)
COPY target/eureka-server-0.0.1-SNAPSHOT.jar eureka-server.jar

# Expose the Eureka server port
EXPOSE 8761

# Run the application
ENTRYPOINT ["java", "-jar", "eureka-server.jar"]
