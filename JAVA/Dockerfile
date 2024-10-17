
# Use the official OpenJDK base image
FROM openjdk:latest
RUN mkdir /app2/tmp
# Set the working directory
WORKDIR /app2/tmp

# Copy the Java program into the container
COPY HelloWorld.java .


# Compile the Java program
RUN javac HelloWorld.java


# Command to run the Java program
CMD ["java", "HelloWorld"]
