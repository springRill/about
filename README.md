## Проектные работы с курса "Мидл Java-разработчик"

### Простое приложение-блог.

https://github.com/springRill/myblog  
В приложении использовано spring, jdbc, thymeleaf, maven.  
PostgreSQL запускается в докере.
Приложение разворачивается на отдельно стоящем tomcat.

https://github.com/springRill/myblog/tree/springboot  
В приложении использовано Spring Boot, jdbc, thymeleaf, gradle.  
PostgreSQL запускается в докере.  
Приложение запускается через IDE (bootJar), или через консоль, после сборки (java -jar myblog-v2.0.jar).

### Витрина интернет магазина.

https://github.com/springRill/intershop  
В приложении использовано Spring Boot, Spring Data JPA, thymeleaf, DB H2, maven.  
Приложение запускается через IDE (IntershopApplication.java).

https://github.com/springRill/intershop/tree/reactive  
В приложении использовано Spring WebFlux, r2dbc, thymeleaf, DB H2, maven.  
Приложение запускается через IDE (IntershopApplication.java).

https://github.com/springRill/intershop/tree/rest-and-redis  
В приложении использовано Spring WebFlux, Spring REST, OpenAPI, Redis, r2dbc, thymeleaf, DB H2, maven.  
Приложение запускается через docker-compose.yml.  

https://github.com/springRill/intershop/tree/auth
В приложении использовано OAuth2(keycloak), Spring WebFlux, Spring REST, OpenAPI, Redis, r2dbc, thymeleaf, DB H2, maven.  
Приложение запускается через docker-compose.yml.  

### Микросервисное приложение «Банк»

https://github.com/springRill/bankapp
В приложении использовано OAuth2(keycloak), Service Discovery(Consul), Distributed Configs(Consul), Spring REST, Spring Data JPA, maven, docker.  
Приложение запускается через docker-compose.yml.  

https://github.com/springRill/bankapp/tree/helm-and-jenkins
В приложении использовано Kubernetes, configmap, OAuth2(keycloak), CI/CD(Jenkins), PostgreSQL.  
Описание запуска в `README.md`.  

https://github.com/springRill/bankapp/tree/kafka  
В приложении использовано Apache Kafka, Kubernetes, configmap, OAuth2(keycloak), CI/CD(Jenkins), PostgreSQL.  
Описание запуска в `README.md`.  

https://github.com/springRill/bankapp/tree/metrics  
В приложении использовано Zipkin, Prometheus/Grafana, ELK, Apache Kafka, Kubernetes, configmap, OAuth2(keycloak), CI/CD(Jenkins), PostgreSQL.  
Описание запуска в `README.md`.  