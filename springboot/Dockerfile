# Use an OpenJDK base image
FROM openjdk:11-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the compiled JAR file into the container
COPY target/ecom-app.jar /app/

# Expose the port your application listens on (if necessary)
EXPOSE 8082

# Command to run the application when the container starts
CMD ["java", "-jar", "ecom-app.jar"]
