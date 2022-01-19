# google-cloud-trace

Download the zip files to the local workspace.

Command to run the projects

cd trace-service-one


./mvnw -DskipTests spring-boot:run -Dspring-boot.run.jvmArguments="-Dserver.port=8080"


cd trace-service-two

./mvnw -DskipTests spring-boot:run -Dspring-boot.run.jvmArguments="-Dserver.port=8080"
