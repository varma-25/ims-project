# Use OpenJDK image
FROM openjdk:21-jdk-slim

# Set working directory
WORKDIR /app

# Copy the JAR file
COPY target/InventoryMgtSystem-0.0.1-SNAPSHOT.jar app.jar

# Expose the port (default Spring Boot port)
EXPOSE 8081

# Run the jar
ENTRYPOINT ["java","-jar","app.jar"]
