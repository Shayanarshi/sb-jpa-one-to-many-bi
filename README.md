
# Spring Boot JPA – One-to-Many Bidirectional

A Spring Boot project demonstrating a Bidirectional One-to-Many relationship using Spring Data JPA and Hibernate.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Oracle Database
- Maven

## Project Overview

This project demonstrates how to map and manage a One-to-Many Bidirectional relationship between entities.

In a bidirectional relationship:
- One parent entity can have multiple child entities.
- Each child entity maintains a reference back to the parent.
- `mappedBy` is used to define the inverse side of the relationship.

```text
Parent
   |
   └── 1 : Many ──> Child
````

## Key Concepts

* `@OneToMany`
* `@ManyToOne`
* `mappedBy`
* JPA Entity Mapping
* Spring Data JPA Repositories
* Hibernate ORM
* Entity Relationships
* Database Persistence

## Project Structure

```text
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
```

## Configuration

Configure the database connection and JPA properties in:

`src/main/resources/application.properties`

## Run the Application

```bash
mvn spring-boot:run
```

You can also run the application directly from your IDE.

## Purpose

This project was created to practice JPA entity relationships, bidirectional mapping, and database operations using Spring Boot.

## Author

**Shayan Arshi**

GitHub: [https://github.com/Shayanarshi](https://github.com/Shayanarshi)
