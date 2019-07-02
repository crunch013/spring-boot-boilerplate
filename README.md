# spring-boot-boilerplate
Maven multi module project with springboot using java 11.

### Project structure
```
* spring-boot-boilerplate
  - model
  - core
```

### Artifacts
```
spring-boot-boilerplate-model-{version}.jar
spring-boot-boilerplate-{version}.jar (core will be named as parent)
```

### Dependencies
```
* model
  - lombok (provided)
  - jackson
    - jdk8
    - jsr310
    - money (org.zalando)
    
* core
  - model
  - moneta
  - log4j (slf4j)
  - spring boot
    - web
    - actuator
    - jetty
    - tests
  - lombok
```
