
# Use the official OpenJDK base image
FROM openjdk:latest
RUN mkdir /app2
# Set the working directory
WORKDIR /app2

# Copy the Java program into the container
COPY HelloWorld.java /app2/naveen

# Compile the Java program
RUN javac HelloWorld.java


# Command to run the Java program
CMD ["java", "HelloWorld"]
