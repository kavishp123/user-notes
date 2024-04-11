FROM openjdk:18

# Copy the packaged Spring Boot application JAR file into the container
COPY target/Users-Notes-0.0.1-SNAPSHOT.jar /app/Users-Notes-0.0.1-SNAPSHOT.jar

# Set the working directory inside the container
WORKDIR /app

# Expose the port that your Spring Boot application runs on
EXPOSE 3000

# Run the Spring Boot application when the container launches
CMD ["java", "-jar", "Users-Notes-0.0.1-SNAPSHOT.jar"]


