=========

## REST Example Project with Spring Security


### Relevant Articles: 
- [Spring Security Expressions - hasRole Example](http://www.baeldung.com/spring-security-expressions-basic)
- [REST Pagination in Spring](http://www.baeldung.com/2012/01/18/rest-pagination-in-spring/)
- [HATEOAS for a Spring REST Service](http://www.baeldung.com/2011/11/13/rest-service-discoverability-with-spring-part-5/)
- [REST API Discoverability and HATEOAS](http://www.baeldung.com/2011/11/06/restful-web-service-discoverability-part-4/)
- [ETags for REST with Spring](http://www.baeldung.com/2013/01/11/etags-for-rest-with-spring/)
- [Error Handling for REST with Spring 3](http://www.baeldung.com/2013/01/31/exception-handling-for-rest-with-spring-3-2/)
- [Integration Testing with the Maven Cargo plugin](http://www.baeldung.com/2011/10/16/how-to-set-up-integration-testing-with-the-maven-cargo-plugin/)
- [Introduction to Spring Data JPA](http://www.baeldung.com/2011/12/22/the-persistence-layer-with-spring-data-jpa/)
- [Project Configuration with Spring](http://www.baeldung.com/2012/03/12/project-configuration-with-spring/)
- [REST Query Language with Spring and JPA Criteria](http://www.baeldung.com/rest-search-language-spring-jpa-criteria)
- [REST Query Language with Spring Data JPA Specifications](http://www.baeldung.com/rest-api-search-language-spring-data-specifications)
- [REST Query Language with Spring Data JPA and QueryDSL](http://www.baeldung.com/rest-api-search-language-spring-data-querydsl)


### Build the Project
```
mvn clean install
```


### Set up MySQL
```
mysql -u root -p 
> CREATE USER 'tutorialuser'@'localhost' IDENTIFIED BY 'tutorialmy5ql';
> GRANT ALL PRIVILEGES ON *.* TO 'tutorialuser'@'localhost';
> FLUSH PRIVILEGES;
```


### Use the REST Service

```
curl http://localhost:8080/spring-security-rest-full/foos
```
