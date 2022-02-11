# Spring Boot ActiveMQ

This project demonstrates a simple microservice that uses Spring Boot and ActiveMQ.

### Run project

``` docker-compose build ```

``` docker-compose up ``` 

And access: ``` http://localhost:8080/ ``` 

### Example

Access Swagger and make a request: ``` http://localhost:8080/swagger-ui.html ```

![Alt text](docs/swagger.png?raw=true "Swagger Request")

Access ActiveMQ console and see message on 'email_queue' queue:

![Alt text](docs/activemq.png?raw=true "ActiveMQ Console")

Check message received on java output console:

![Alt text](docs/listener.png?raw=true "List")