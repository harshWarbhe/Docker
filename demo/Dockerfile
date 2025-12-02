# Step 1: Use Java runtime
FROM eclipse-temurin:21-jdk

# Step 2: Add jar file to container
ADD target/demo-0.0.1-SNAPSHOT.jar app.jar

# Step 3: Run the jar
ENTRYPOINT ["java","-jar","/app.jar"]