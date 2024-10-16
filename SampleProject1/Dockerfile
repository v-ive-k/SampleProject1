# 1. Use an official OpenJDK runtime as a parent image
FROM openjdk:17-alpine

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Copy the HelloWorld.java file from your local machine into the container at /app
COPY src\main\java\com\example\App .

# 4. Compile the HelloWorld.java file
<<<<<<< HEAD
RUN javac App
=======
RUN mvn clean package -DskipTests
>>>>>>> 69940bc275dbd837c7c2dcd449cecaf7893e0ead

# 5. Run the compiled HelloWorld class
CMD ["java", "App"]
