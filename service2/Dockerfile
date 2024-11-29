# Use OpenJDK image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the jar file from target directory to the working directory
COPY target/service2-1.0.jar /app/service2.jar

# Expose the port that Spring Boot is running on
EXPOSE 8080

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app/service2.jar"]
