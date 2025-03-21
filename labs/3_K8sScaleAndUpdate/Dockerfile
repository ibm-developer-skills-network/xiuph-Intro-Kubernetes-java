# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from your local machine into the container
COPY target/*.jar app.jar

# Expose the port on which the application will run
EXPOSE 8080

# Command to run the JAR file
CMD ["java", "-jar", "app.jar"]
