# 1. Use an official OpenJDK runtime as a parent image
FROM openjdk:17-alpine

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Copy the HelloWorld.java file from your local machine into the container at /app
COPY /var/lib/jenkins/workspace/secondproject/SampleProject1/src/main/java/com/example/HelloWorld .

# 4. Compile the App.java file
RUN mvn clean package

# 5. Run the compiled App class
CMD ["java", "App"]
