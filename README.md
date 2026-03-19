# 📱 Phone Store Application

## 📌 Introduction

Phone Store Application is a web-based system developed using **Java Spring Boot**.
This project simulates an online mobile phone store where users can browse products, manage a shopping cart, and create invoices.

The application is designed for learning purposes, focusing on backend development, RESTful APIs, and database integration.

---

## 🚀 Features

* 👤 User authentication (Login/Register)
* 📦 Product management (CRUD operations)
* 🛒 Shopping cart (Add / Update / Remove items)
* 🧾 Invoice & order management
* 📡 RESTful API support
* 🗄️ MySQL database integration

  
admin's account :admin
admin1234



---

## 🛠️ Technologies Used

* Java (Spring Boot)
* Maven
* MySQL
* JPA / Hibernate
* RESTful API

---

## 📂 Project Structure

```
src/main/java/
├── controller        # Handle HTTP requests
├── apicontroller     # REST APIs
├── service           # Business logic
├── repository        # Database access
├── model             # Entity classes
├── dto               # Data transfer objects
```

---

## ⚙️ Setup & Installation

### 1. Clone project

```
git clone https://github.com/your-username/phone-store-application.git
```

### 2. Configure database

Update `application.properties`:

```
spring.datasource.url=jdbc:mysql://localhost:3306/phone_store
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 3. Run application

```
mvn spring-boot:run
```

---

## 📡 API Example

* GET `/api/products` → Get all products
* POST `/api/products` → Add new product
* POST `/api/invoices` → Create invoice

---

## 🎯 Project Purpose

* Practice Java Spring Boot development
* Understand MVC architecture
* Build RESTful APIs
* Work with MySQL database

---

## 📌 Notes

* This project is for learning purposes only
* Not optimized for production use

---

## ⭐ Future Improvements

* Add frontend (React / Angular)
* Payment integration
* Product search & filter
* Deploy to cloud

---
