## Spring Boot Data with JPA-Hibernate ORM and H2 Database

### Spring Data JPA:
Spring Data JPA, part of the larger Spring Data family, makes it easy to easily implement JPA based repositories. This module deals with enhanced support for JPA based data access layers. It makes it easier to build Spring-powered applications that use data access technologies.

### JPA (Java Persistence API):
JPA is not a tool or framework; rather, it defines a set of concepts that can be implemented by any tool or framework. While JPA's object-relational mapping (ORM) model was originally based on Hibernate, it has since evolved. Likewise, while JPA was originally intended for use with relational/SQL databases, some JPA implementations have been extended for use with NoSQL datastores. A popular framework that supports JPA with NoSQL is EclipseLink,

### Hibernate ORM:
Hibernate ORM is an object-relational mapping tool for the Java programming language. It provides a framework for mapping an object-oriented domain model to a relational database

### H2 Database:
H2 is the Java SQL database
- Very fast, open source, JDBC API
- Embedded and server modes; in-memory databases
- Browser based Console application
- Small footprint: around 2 MB jar file size

further references:     
- https://spring.io/projects/spring-data-jpa
- https://www.infoworld.com/article/3379043/what-is-jpa-introduction-to-the-java-persistence-api.html
- http://www.h2database.com/html/main.html  


### Project descriptions :
please see application.properties files in resources folder and select a active profile "dev" or "com" to run project. you can check test methods too.  

to manage embedded h2 database open <a href='http://localhost:8080/h2-console/' target='_blank'>http://localhost:8080/h2-console/</a> with 
- username:sa
- password: (blank password) 
- datasourceUrl: jdbc:h2:mem:motahariniadb'
<hr/>
<a href="mailto:eng.motahari@gmail.com?"><img src="https://img.shields.io/badge/gmail-%23DD0031.svg?&style=for-the-badge&logo=gmail&logoColor=white"/></a>

