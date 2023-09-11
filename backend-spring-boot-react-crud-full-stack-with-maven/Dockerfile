# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled JAR file into the container at the specified path
COPY target/spring-boot-fullstack-crud-full-stack-with-maven-0.0.1-SNAPSHOT.jar /app/spring-boot-fullstack-crud-full-stack-with-maven-0.0.1-SNAPSHOT.jar

# Expose the port that your Spring Boot application will run on
EXPOSE 8080

# Define environment variables if needed (e.g., for Spring Profiles)
# ENV SPRING_PROFILES_ACTIVE=production

# Command to run your application
CMD ["java", "-jar", "spring-boot-fullstack-crud-full-stack-with-maven-0.0.1-SNAPSHOT.jar"]
