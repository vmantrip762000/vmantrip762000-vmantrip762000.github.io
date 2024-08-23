---
layout: project
type: project
image: img/calcimage.png
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
  <img width="200px" src="../img/bandwcalc.png" class="img-thumbnail" >
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
Enhanced User Experience: The calculator provides real-time results and allows continuous operations without restarting the application.
Modular and Scalable Design: The use of OOP principles ensures that the code is modular, maintainable, and easy to extend with additional features.
Efficient Error Handling: Integrated error handling mechanisms to manage invalid inputs and prevent runtime errors, ensuring a smooth user experience.

Here is a code sample that illustrates the functions implemented in calculator application:

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

You can learn more about the source code of employee log book CLI in my GitHub repository at [Simple Arithmetic Calculator](https://github.com/vmantrip762000/arithematic-calculator).
