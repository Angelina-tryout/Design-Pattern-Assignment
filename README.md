# Design-Pattern-Assignment
In this project, you will implement an application that returns disease statistics using design patterns.


1. Build the project using maven command `mvn clean install -DskipTests`. First time build will consume time as it downloads all dependencies.     ```

output

[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  7.348 s
[INFO] Finished at: 2024-02-11T13:09:43+05:30
[INFO] ------------------------------------------------------------------------

2. Start the application using command `mvn spring-boot:run`

3. Open this in browser to check the health of URL ->  http://localhost:8080/actuator/health

Output should show as below

{"status":"UP"}
