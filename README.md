# spring-kafka-microservice
This is a repository for building a Spring Boot microservice using NetflixOSS and Apache Kafka.

- Check
  - http://localhost:8761/
  
#### Test Microservice
Once each micro service is setup and started correctly, you can test the complete flow by
1. Create a new user by calling url – POST http://localhost:8081/register
2. Verify that the new user is created.
3. You can also verify the user by calling – GET http://localhost:8081/member
4. Verify that registration success email was received at your email address
