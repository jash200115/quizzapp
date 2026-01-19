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
  <img width="1919" height="1142" alt="image" src="https://github.com/user-attachments/assets/e0a49d4b-1518-495d-9e34-085001728c04" />
  <img width="800" height="489" alt="image" src="https://github.com/user-attachments/assets/00eb3c41-a121-4b0e-8b3d-065cb30d13ae" />
  <img width="591" height="437" alt="image" src="https://github.com/user-attachments/assets/0a83851c-f466-48d6-8b58-ca72ded1b53e" />

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
