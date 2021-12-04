# TQI Java Developer Bootcamp Projects
### Criando seu gerenciador de super heróis da Marvel e da DC em uma API reativa com Spring Boot
In this application has been developed an API for creating heroes :-) using Spring WebFlux and reactive libraries.  
DynamoDB is the database used for this project and the Swagger the documentation library.

In order to use this project you need:
- Java >= 8;
- install and setup on your local machines the AWS CLI 2;
- install DynamoDB standalone version.
- use in proper way the application.properties file [src/main/resources/application.properties](src/main/resources/application.properties)
```
aws_access_key_id = don't put your key here, the aws cli key will be used
aws_secret_access_key = don't put your key but only the field name
amazon.dynamodb.endpoint=http://localhost:8000
spring.autoconfigure.exclude=org.springframework.boot.autoconfigure.jdbc.DataSourceAutoConfiguration
springdoc.swagger-ui.path=/swagger-ui-heroes-reactive-api.html
```

