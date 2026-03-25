# backend/Dockerfile
FROM openjdk:17-jdk-slim

# Set workdir
WORKDIR /app

# Copy jar built by Maven
COPY target/myapp.jar myapp.jar

# Expose port your Spring Boot app runs on
EXPOSE 8080

# Run the app
ENTRYPOINT ["java", "-jar", "myapp.jar"]
