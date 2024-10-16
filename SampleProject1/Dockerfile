# 1. Use an official OpenJDK runtime as a parent image
FROM openjdk:17-alpine

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Copy the HelloWorld.java file from your local machine into the container at /app
COPY src\main\java\com\example\App .

# 4. Compile the HelloWorld.java file
RUN javac App

# 5. Run the compiled HelloWorld class
CMD ["java", "App"]
