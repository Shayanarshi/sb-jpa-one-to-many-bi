# Spring Boot JPA – One-to-Many Bidirectional

A Spring Boot project demonstrating how to implement and manage a **Bidirectional One-to-Many relationship** using **Spring Data JPA and Hibernate**.

## 🚀 Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Oracle Database
- Maven

## 📌 Project Overview

This project focuses on mapping a **One-to-Many Bidirectional relationship** between entities.

A parent entity can be associated with multiple child entities, while each child entity maintains a reference back to its parent.

```text
Parent
  │
  └─── 1 : Many ───> Child



🔑 Key Concepts
@OneToMany
@ManyToOne
mappedBy
JPA Entity Mapping
Spring Data JPA Repositories
Hibernate ORM
Entity Relationships
Database Persistence
📂 Project Structure
src/
└── main/
    ├── java/
    │   └── in/ashokit/
    │       ├── model/
    │       ├── repository/
    │       └── runner/
    │
    └── resources/
        └── application.properties
⚙️ Configuration

Configure the database connection and JPA properties in:

src/main/resources/application.properties
▶️ Run the Application
mvn spring-boot:run

Or run the Spring Boot application directly from your IDE.

🎯 Purpose

This project was created to practice JPA entity relationships, bidirectional mapping, and database operations using Spring Boot.

👨‍💻 Author

Shayan Arshi
