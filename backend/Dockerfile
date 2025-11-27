# Use official Eclipse Temurin JDK (OpenJDK) image
FROM eclipse-temurin:21-jdk

# Set working directory
WORKDIR /app

# Copy JAR file
COPY target/*.jar app.jar

# Expose backend port
EXPOSE 5050

# Run application
ENTRYPOINT ["java", "-jar", "app.jar"]
