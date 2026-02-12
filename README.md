📝 NotEPK – Secure Notes Management System

TakeNote is a secure, full-stack web application built using Spring Boot that allows users to create, manage, and organize personal notes.
The application integrates Spring Security, JPA/Hibernate, and MySQL to deliver a production-ready backend system with authentication and relational data management.

🚀 Project Highlights

🔐 Secure user authentication using Spring Security

🗂 Create, update, delete, and manage notes

👤 User–Note relationship (One-to-Many mapping)

🛢 MySQL database integration

⚡ RESTful & MVC architecture

📦 Maven-based dependency management

🧠 Clean layered architecture (Controller → Service → Repository)

🛠 Tech Stack
Backend

Java 17

Spring Boot

Spring Data JPA

Hibernate ORM

Spring Security

MySQL

Maven

Tools

VS Code / IntelliJ

Postman

MySQL Workbench

📁 Project Structure
Take-Note
 ├── src/main/java
 │    ├── controller
 │    ├── service
 │    ├── repository
 │    ├── model
 │    └── config
 ├── src/main/resources
 │    ├── application.properties
 │    └── templates
 ├── pom.xml
 └── mvnw

⚙️ How to Run the Project
1️⃣ Clone the repository
git clone <your-repo-link>
cd NotEPK

2️⃣ Configure Database

Create MySQL database:

CREATE DATABASE takenote;


Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/NotEPK
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

3️⃣ Run the Application

Using Maven wrapper:

.\mvnw.cmd spring-boot:run


OR

mvn spring-boot:run

4️⃣ Access Application

Open browser:

http://localhost:8080

🔐 Security Features

Authentication enabled via Spring Security

Secure login system

Role-based access (if configured)

Password protected user data

🧩 Database Design
User Table

id

name

email

password

role

phone

address

gender

Notes Table

id

title

description

created_at

user_id (Foreign Key)

🎯 Key Learning Outcomes

Implemented secure authentication with Spring Security

Designed relational database schema with foreign key constraints

Applied JPA entity relationships and Hibernate ORM

Built scalable layered architecture following industry standards

Managed project dependencies using Maven

👨‍💻 Developed By

Prashant Kumar
Backend / Full Stack Developer