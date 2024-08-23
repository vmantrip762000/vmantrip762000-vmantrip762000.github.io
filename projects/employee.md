---
layout: project
type: project
image: img/logbook.png
title: "Log book application"
date: 2024
published: true
labels:
  - OOPs programming
  - Java
  - IntelliJ
summary: "Developed a Spring Boot application with Apache Maven."
---

<div class="text-center p-4">
  <img width="200px" src="../img/cli.png" class="img-thumbnail" >
</div>

**Employee log book application**

Project Description:
Developed a Spring Boot application with Apache Maven build logging tasks.

**Key Features and Functions**
***MainController.java****: It handles HTTP requests related to user data, with key methods to create new users (addNewUser) and retrieve all users (getAllUsers).

***User.java***: Used to represent a user entity, containing attributes like id, name, and email. It uses JPA annotations to define the entity and primary key.

***UserRepository.java***: provides CRUD operations for user entities by extending CrudRepository, offering basic CRUD functionality.

***application.properties***: configures Spring Boot application properties, including the application name (spring.application.name), database schema update behavior (spring.jpa.hibernate.ddl-auto), database connection URL (spring.datasource.url), database username and password (spring.datasource.username, spring.datasource.password), and JDBC driver class (spring.datasource.driver-class-name).

***DemoApplicationTests.java***: is a basic test class that verifies application context loading with the contextLoads() method.

***mvn/wrapper***: defines Maven wrapper configuration, specifying the wrapper version and distribution URL.

**Outcome and Impact**
The Employee Log Book application, built with Spring Boot and Apache Maven, provides a scalable and efficient solution for managing employee data. Apache Maven streamlined development by managing dependencies and automating build tasks. The application leverages OOP principles and cloud-based data storage for efficient data management. API testing with Postman ensured reliability. Overall, the application delivers a valuable tool for managing employee information.

Here is a code sample that illustrates the User class implemented in logbook application:

```java
@Entity
public class User {

  @Id
  @GeneratedValue(strategy = GenerationType.IDENTITY)
  private Integer id;

  private String name;

  private String email;   


  // Getters and setters omitted for brevity

}
```

You can learn more about the source code of employee log book CLI in my GitHub repository at [Employee Log Book application](https://github.com/vmantrip762000/Springboot-management-application).
