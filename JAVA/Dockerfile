
# Use the official OpenJDK base image
FROM openjdk:latest
RUN mkdir /app
# Set the working directory
WORKDIR /app

# Copy the Java program into the container
COPY HelloWorld.java .

# Compile the Java program
RUN javac HelloWorld.java

# Command to run the Java program
CMD ["java", "HelloWorld"]
