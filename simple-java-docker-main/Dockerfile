# stable official Java runtime base image
#FROM openjdk:17-jdk-alpine

# FROM openjdk:17-jdk-alpine is not run then use (eclipse temurin is an OpenJDK distribution maintained by the Eclipse Adoptium project)
FROM eclipse-temurin:17-jdk-alpine


# working directory
WORKDIR /app

# Copy source code into the container
COPY src/Main.java /app/Main.java

# Compile the Java code
RUN javac Main.java

# Run the Java application when the container starts
CMD ["java", "Main"]
