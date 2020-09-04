![](https://github.com/Lylio/helper-repo/blob/master/img/logos/java.png?raw=true)
![](https://github.com/Lylio/helper-repo/blob/master/img/logos/spring-boot.png?raw=true)
# Eureka-Discovery-Services
## Built with Spring Boot

### Description
A Spring Boot a Spring Boot application based on Netflix's Eureka service discovery server.

#### Docker Launch
1. `docker build -t eureka-discovery-services .`
2. `docker run -p 8010:8010 eureka-discovery-services:latest`

#### Maven Launch
1. `./mvnw spring-boot:run`
2. Open tab/browser at http://localhost:8010 to confirm Eureka is running