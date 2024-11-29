# Use OpenJDK image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the jar file from target directory to the working directory
COPY target/api-gateway-1.0.jar /app/api-gateway.jar

# Expose the port that Spring Boot is running on
EXPOSE 8081

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app/api-gateway.jar"]
