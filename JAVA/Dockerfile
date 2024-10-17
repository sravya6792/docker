FROM openjdk:11-jre-slim
RUN mkdir /app
WORKDIR /app
RUN pwd
COPY hello.java .
RUN javac hello.java
CMD ["java","hello"]