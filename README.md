# <h1 align = "center">  UserMnangement </h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->
## Overview
<p align="center">This project,   Insta Basic ," is a robust Spring Boot application designed for managing user data efficiently. It provides a set of API endpoints that allow you to perform various operations on user records, such as adding, retrieving, updating, and deleting user information. 
</p>

<!-- Table of Contents -->
## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->
## Technologies Used
- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- SQL DRIVER
- JPA
- SWAGGER
- sQL DATABASE
- OneToOne Mapping
- OneToMany Mapping
- ManyToMany Mapping
- ManyToOne Mapping

## Model Classes
1. MyPermission Model
The MyPermission Model handles permissions within the HMS system, defining the various actions and access levels that users can have.
2. Role Model
The Role Model defines the roles and their associated permissions within the system. It's crucial for user authorization and access control.
3. User Model
The User Model manages user-related data, such as authentication, user details, and roles assigned to each user.
4. UserProfile Model
The UserProfile Model stores additional information about users, including contact details, medical history, and other relevant personal information.
## Controller Class
1. MyPermission Controller
The MyPermission Controller is responsible for handling permissions and their associated actions within the HMS system. It enables the management of permissions and their assignments to roles and users.
2. Role Controller
The Role Controller manages roles and their associated permissions. It is crucial for user authorization and access control within the system.
3. User Controller
The User Controller handles user-related operations, including user authentication, user details management, and the assignment of roles to users.
4. UserProfile Controller
The UserProfile Controller is responsible for managing additional user information, such as contact details, medical history, and other personal data.
Features
Logic for managing permissions, roles, users, and user profiles.
Role-based access control to restrict access to specific functionalities.
CRUD (Create, Read, Update, Delete) operations for each entity.
User authentication and authorization.
## Service Class
1. MyPermission Service
The MyPermission Service is responsible for executing operations related to permissions within the HMS system. It allows for the management of permissions and their assignments to roles and users.
2. Role Service
The Role Service manages operations related to roles and their associated permissions. It plays a crucial role in user authorization and access control within the system.
3. User Service
The User Service handles user-related operations, including user authentication, user details management, and the assignment of roles to users.
4. UserProfile Service
The UserProfile Service is responsible for executing operations related to additional user information, such as contact details, medical history, and other personal data.


<!-- Key Features -->
## Key Features
- Get Student by Id.
- Get all Sudent.
- Get Student Details By Id.
- Delete Course By Id.
- Update StudentName
- SingUp
- SingIn

<!-- Usage -->
## Usage
- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to CRUD Operation And Custom finder.

### Controller:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.

### API Reference

#### Add Users :
PostMethod :  http://localhost:8080/posts
### UPdate User:
PutMapping : http://localhost:8080/companyName/Id

### Delete User:
DeleteMapping: http://localhost:8080/Delete/Id/


#### Get All Users :
 - GET Method : http://localhost:8080/get

 

 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact
For questions or feedback, please contact : SHRAVAN KUMAR   -
- Maild Id : shravankm93@gmail.com

<h1 align="center">Thank You...<h1>
<h3 align = "center"> ***********************************************************<h3>
*  Insta Basic 
