# Quiz App (Spring Boot)

A backend Quiz Application built using **Java, Spring Boot, Spring Data JPA**, and **PostgreSQL**.  
This project is created as part of my learning journey into backend development and Spring Boot.

---

## 🛠 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- IntelliJ IDEA

---

## 📌 Features

- REST APIs for quiz management
- Database persistence using PostgreSQL
- JPA/Hibernate for ORM
- Clean layered architecture (Controller, Service, Repository)

---

## 🗄 Database

This project uses **PostgreSQL** as the database.

### Database Configuration (example)

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/quizzapp
spring.datasource.username=postgres
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
