# 1. Use an official OpenJDK runtime as a parent image
FROM openjdk:17-alpine

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Copy the HelloWorld.java file from your local machine into the container at /app
COPY src/main/java/com/example/HelloWorld .

# Debugging: List files to ensure the copy was successful
RUN ls -la .

# 4. Compile the App.java file
RUN javac HelloWorld

# 5. Run the compiled App class
CMD ["java", "App"]
