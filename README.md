# 📚 Library Management System (EBS)

A **Spring Boot** powered Library Management System designed for managing students, books, authors, and transactions in a college library.  
It allows students to register, issue/return books, and manage their accounts securely.

---

## 🚀 Features

- 👤 **Student Management**: CRUD operations for students with auto card generation  
- 📖 **Book & Author Management**: CRUD operations for books and authors  
- 🧾 **Transactions**:
  - Issue and return books with constraints
  - Fine calculation for late returns
  - Unique transaction UUID tracking  
- 🔐 **Authentication & Authorization**:
  - Student & Admin roles via **Spring Security**
  - Role-based access control for APIs
- 🗄 **Persistence**:
  - MySQL database integration
  - JPA/Hibernate for ORM
- 🛡 **Business Logic**:
  - Card activation/deactivation
  - Book availability checks
  - Transaction limits for issued books

---

## 🛠 Tech Stack

- **Java 11+**
- **Spring Boot 2.4.3**
- **Spring Data JPA (Hibernate)**
- **Spring Security**
- **MySQL**
- **Lombok**
- **Maven**

---

## ⚡ Getting Started

### Prerequisites
- Java 11+
- Maven
- MySQL running locally

### Run Locally (CLI)
```bash
git clone https://github.com/Anshumaan13/EBS.git
cd EBS
mvn clean package
java -jar target/Student-library-0.0.1-SNAPSHOT.jar
