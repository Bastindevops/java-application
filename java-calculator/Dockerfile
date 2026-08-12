# Use a lightweight Eclipse Temurin Java 17 JRE Alpine runtime base image
FROM eclipse-temurin:21-jre-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the pre-built jar file from your local target directory into the container
COPY target/java-calculator-1.0.0.jar app.jar

# Expose the application port (matches your application.properties or default)
EXPOSE 9200

# Run the jar file
ENTRYPOINT ["java", "-jar", "app.jar"]
