# Currency-App-Microservices
A Microservices Application implementation using Spring Boot and Spring Cloud

## Components
- Storing all configurations centrally at *Spring Cloud Config Server*
- *Feign Client* to communicate between different microservices.
- Load Balancing with *Ribbon*
- Service Registration and Discovery using *Netflix Eureka Naming Server*
- Each request intercepted through *Zuul API Gateway Server*
- Distributed Tracing using *Zipkin*
- Fault Tolerance using *Hystrix*
