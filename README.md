## Spring Boot User Module CRUD Operations Tutorial
This repository contains the source code on developing a Java web application using Spring Boot, IntelliJ IDEA, and various other technologies. 
This is my first Java Project to implement the User module with CRUD operations (Create, Read, Update, and Delete).

### Software Programs Required
-Java Development Kit (OpenJDK)

-IntelliJ IDEA Ultimate

-MySQL Community Server

-MySQL Workbench

### Technologies Used
-Spring Boot Web

-Spring Data JPA & Hibernate

-MySQL Database

-Thymeleaf

-Spring Data JPA Test

## Setting up

1.To run the "spring-boot-crud-intellij" project in IntelliJ IDEA, follow these steps:
Clone the Repository: 
```git clone https://github.com/solojh/spring-boot-crud-intellij.git```

2.Open IntelliJ IDEA

3.Open the Project: Click on File > Open the directory where you cloned the "spring-boot-crud-intellij" repository. Select the root folder of the project and click OK.

4.Configure MySQL Database: Make sure you have MySQL Community Server installed and running on your system. 
```spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name```
```spring.datasource.username=your_mysql_username```
```spring.datasource.password=your_mysql_password```

5.Run the Application: MyWebAppApplication.java file located in the src/main/java/com.mycompany directory. 

6.Visit http://localhost:8000 to see the website

![2](https://github.com/solojh/Spring-Boot-CRUD-Java-Employee-Management-System/assets/97234810/6ab25cb9-2670-46e5-8edf-6d878a75fa69)

### API Endpoint
```Get All Employees
Method: GET
Path: /employees
Description: Retrieves a list of all employees.

Create New Employee
Method: POST
Path: /employees/save
Description: Creates a new employee.

Edit Employee
Method: GET
Path: /employees/edit/{id}
Description: Retrieves the employee with the specified ID for editing.

Delete Employee
Method: GET
Path: /employees/delete/{id}
Description: Deletes the employee with the specified ID.
```




