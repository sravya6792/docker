# Use the official OpenJDK base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the Java program into the container
COPY hello.java .

# Compile the Java program
RUN javac hello.java

# Command to run the Java program
CMD ["java", "hello"]

