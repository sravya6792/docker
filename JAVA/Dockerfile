
# Use the official OpenJDK base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the Java program into the container
COPY HelloWorld.java .

# Compile the Java program
RUN javac HelloWorld.java

# Command to run the Java program
CMD ["java", "HelloWorld"]
