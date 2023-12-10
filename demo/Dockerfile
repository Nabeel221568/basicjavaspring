# Use an official Java runtime as a parent image
FROM openjdk:21-jdk

# Set the working directory in the container
WORKDIR /app

# Copy the jar file into the container at /app
COPY target/demo-0.0.1-SNAPSHOT.jar /app/demo.jar

# Run the jar file 
ENTRYPOINT ["java","-jar","demo.jar"]
