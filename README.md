# 💼 Smart Inventory Management System (Java + MySQL)

A simple **Java-based Inventory Management System** that helps manage product details, stock, and pricing efficiently using **JDBC** and **MySQL**.

## 🧰 Tools & Technologies
- Java (JDK 8+)
- MySQL
- JDBC
- MySQL Connector/J
- IDE: Eclipse / IntelliJ IDEA / NetBeans

## ⚙️ Features
✅ Add, View, Update, Delete Products  
✅ Database Connectivity via JDBC  
✅ Console-based Interface  
✅ Easy Setup for Beginners

## 🗄️ Database Setup (MySQL)
Run this script in MySQL:

```sql
CREATE DATABASE inventory_db;
USE inventory_db;
CREATE TABLE products (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  quantity INT,
  price DOUBLE
);
```

## 🚀 How to Run
1. Import the project into your IDE.
2. Add MySQL Connector JAR to classpath.
3. Update MySQL credentials in `DBConnection.java`.
4. Compile and Run `InventoryApp.java`.

## 👨‍💻 Author
**Sree Lingeshwaran S**  
Aspiring Associate System Engineer @ IBM
