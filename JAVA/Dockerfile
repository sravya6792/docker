
# Stage 1: Build the Java program
FROM openjdk:latest

# Set the working directory
RUN mkdir /app2
WORKDIR /app2

# Copy the Java program into the container
COPY HelloWorld.java /app2

# Compile the Java program
RUN javac HelloWorld.java

# Stage 2: Run the Java program
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the compiled Java program from the builder stage
COPY --from=builder /app/HelloWorld.class .

# Command to run the Java program
CMD ["java", "HelloWorld"]
