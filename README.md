# 🎓 Campus Connect

**Campus Connect** is a Java Swing-based **University Management System** desktop application built to manage academic data and streamline campus operations. It allows administrators to manage students, faculty, courses, and attendance efficiently with a graphical interface and robust backend.

---

## 🚀 Features

- 🧑‍🎓 Student & Faculty Registration and Management
- 📚 Course and Subject Management
- 🔐 Secure Login System
- 📂 Java Swing GUI with AWT components
- 💾 MySQL Database Integration using JDBC

---

## 🛠️ Tech Stack

- **Java (Core, Swing, AWT)**
- **MySQL** (Relational Database)
- **JDBC** (Java Database Connectivity)
- **NetBeans IDE** (or any Java-compatible IDE)

---

## 🗄️ Database Setup (MySQL)

1. Install MySQL Server on your system.
2. Create a database (e.g., `campus_connect_db`)
3. Import the SQL schema file (if provided), or manually create tables based on the project.
4. Update the database connection credentials in the Java source files, usually in a file like `DbConnection.java`:

```java
String url = "jdbc:mysql://localhost:3306/campus_connect_db";
String user = "root";
String password = "your_mysql_password";
