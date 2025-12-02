# Step 1: Use Java runtime
FROM eclipse-temurin:17-jdk

# Step 2: Add jar file to container
ADD target/myapp-1.0-SNAPSHOT.jar app.jar

# Step 3: Run the jar
ENTRYPOINT ["java","-jar","/app.jar"]