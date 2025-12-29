# Student Management System

Student Management System is a simple CRUD web application built using Spring Boot, Spring MVC, Spring Data JPA, Thymeleaf, and Bootstrap.

This application is used to manage student records including adding, viewing, updating, and deleting students.

---
### Create
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/54ffe821-fd3c-41a2-a0e2-b70923b0d07f" />

### Read
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2bef4911-2b1c-4772-a2df-f57069909d5b" />

### Update
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b75ddb49-3764-4056-9d2d-88d02979237c" />

### Delete
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2bef4911-2b1c-4772-a2df-f57069909d5b" />




## Features
- Add new student
- View all students
- Update student details
- Delete student records
- Simple home page navigation

---

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- Thymeleaf
- HTML
- CSS
- Bootstrap

### Database
- MySQL

### Dependency Management Tool
- Maven

---

## Project Structure

com.StudentManagementSystem  
├── controller  
│   └── Controller.java  
├── entity  
│   └── Student.java  
├── repository  
│   └── Studentrepository.java  
├── service  
│   └── StudentService.java  
├── serviceImpl  
│   └── ServiceImpl.java  
└── resources  
&nbsp;&nbsp;&nbsp;&nbsp;├── templates  
&nbsp;&nbsp;&nbsp;&nbsp;│   ├── home.html  
&nbsp;&nbsp;&nbsp;&nbsp;│   ├── students.html  
&nbsp;&nbsp;&nbsp;&nbsp;│   ├── create-student.html  
&nbsp;&nbsp;&nbsp;&nbsp;│   └── edit_student.html  
&nbsp;&nbsp;&nbsp;&nbsp;└── static

---

## Application Flow
1. The user sends a request from the browser
2. The controller handles the request
3. The service layer processes business logic
4. The repository communicates with the database
5. Data is passed to Thymeleaf views
6. The response is displayed to the user

---

## How to Run the Project
1. Clone the repository
2. Configure MySQL database in `application.properties`
3. Run the project using `mvn spring-boot:run`
4. Open `http://localhost:8080/home` in the browser

---

## Purpose
This project is created for learning and practice of Spring Boot CRUD
operations and MVC architecture.
