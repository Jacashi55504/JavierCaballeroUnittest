# Unittest Project - Software Quality

## Author
**Javier Caballero**

## Course
Software Quality 

## Description
This repository contains the project developed during one of Software Quality class. The focus of this assignment is to implement unit tests for the `UserService` class, covering CRUD operations using JUnit and Mockito.

## Evidence of Test and Execution

## Project Requirements
Implement unit tests for the following `UserService` CRUD functionalities:
1. **Create a new user**
   - **Happy path**: All data is correct.
   - **Duplicated email**: No user is created if the email already exists.
2. **Update user**
3. **Update password**
4. **Delete user**
5. **Find a user by email**
   - **Happy path**: User is found.
   - **User not found**: No user is returned if the email does not exist.
6. **Find all users**

## Tools and Technologies
- **Java 17**
- **JUnit 5**: For creating and running tests.
- **Elcipse**: IDE used for the project.

## Project Structure
unittest/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/
│   │           └── mayab/
│   │               └── quality/
│   │                   └── logginunittest/
│   │                       └── service/
│   │                           └── UserService.java
│   │
│   └── test/
│       └── java/
│           └── com/
│               └── mayab/
│                   └── quality/
│                       └── unittest/
│                           └── service/
│                               └── UserServiceTest.java
│
├── LICENSE
├── pom.xml
└── README.md
