# Spring Boot : Application PetClinic

## Features  

### 1.  Unit Test  --> Tag v1.0.0
### 2.  Integration Test  --> Tag v2.0.0
### 3.  Load Test  --> Tag v3.0.0

#### - mvn test -P dev  --> aplication-dev.properties
#### - mvn test -P test --> aplication-test.properties
#### - mvn test -P prod --> aplication-prod.properties

### 4.  Integracion continua (Lab 13) --> Jenkins en AWS EC2

#### - Jenkinsfile: Checkout -> Build (mvn clean compile) -> Test (mvn test) -> Package (mvn package -DskipTests)
#### - Cada push a main dispara el pipeline por el webhook de GitHub (/github-webhook/)
