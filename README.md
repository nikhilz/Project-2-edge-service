# Project:2 edge-service
 it will have fallback capabilities which prevent the client from receiving an HTTP error when the service is not available

item-catalog service : https://github.com/nikhilz/project-2-Item-catelog

Eureka Server: https://github.com/nikhilz/Project-2-EurekaServer

# Dependencies used:

* Eureka Discovery: for service registration
* Feign: a declarative web service client
* Zuul: provides intelligent routing
* Rest Repositories: to expose JPA repositories as REST endpoints
* Web: Spring MVC and embedded Tomcat
* Hystrix: a circuit breaker to stop cascading failure and enable resilience
* Lombok: to reduce boilerplate code
