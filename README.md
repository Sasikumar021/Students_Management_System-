# 🎓 Student Management System using Python & MySQL

## 📌 Project Overview

The **Student Management System** is a menu-driven CRUD (Create, Read, Update, Delete) application developed using **Python** and **MySQL**. It is designed to manage student records efficiently by allowing users to add, search, update, display, and delete student information stored in a MySQL database.

The project demonstrates how Python can be integrated with MySQL using the **mysql-connector-python** library. It provides a simple command-line interface that enables users to perform database operations easily while ensuring data is stored permanently in MySQL.

---

## ✨ Features

- ➕ Add new student records
- 🔍 Search students by Student ID
- ✏️ Update student marks
- 📋 Display all student records
- ❌ Delete student records
- 💾 Permanent data storage using MySQL
- 📌 Menu-driven user interface

---

## 🛠️ Technologies Used

- **Programming Language:** Python 3.x
- **Database:** MySQL 8.0
- **Connector:** mysql-connector-python
- **IDE:** Jupyter Notebook / VS Code
- **Operating System:** Windows 10/11

---

## 🗄️ Database Schema

### Create Database

```sql
CREATE DATABASE student_management;
```

### Use Database

```sql
USE student_management;
```

### Create Table

```sql
CREATE TABLE students(
    student_id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    gender VARCHAR(10),
    course VARCHAR(50),
    mobile VARCHAR(20),
    marks FLOAT
);
```

---

### 4. Configure MySQL Connection

Update the database credentials inside the Python file.

```python
mydb = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="student_management"
)
``
---

## 📖 Menu Options

```text
========== STUDENT MANAGEMENT SYSTEM ==========

1. Add Student
2. Update Marks
3. Search Student
4. Display All Students
5. Delete Student
6. Exit
```

---

## 🧩 Functional Modules

### ➕ Add Student

Adds a new student record to the database.

### ✏️ Update Marks

Updates the marks of an existing student.

### 🔍 Search Student

Searches student details using Student ID.

### 📋 Display All Students

Displays all student records stored in the database.

### ❌ Delete Student

Deletes a student record using Student ID.

### 🚪 Exit

Closes the database connection and exits the application.

---

## 🗃️ Sample Student Record

| Student ID | Name | Course | Marks |
|------------|------|--------|------:|
| 107 | P. Sasi Kumar | ECE | 94 |

---

## 🔄 CRUD Operations

| Operation | SQL Command |
|-----------|-------------|
| Create | INSERT |
| Read | SELECT |
| Update | UPDATE |
| Delete | DELETE |

---

## 📚 Python Concepts Used

- Functions
- Loops
- Conditional Statements
- User Input
- SQL Queries
- MySQL Database Connectivity
- CRUD Operations
- Cursor Object
- `fetchone()`
- `fetchall()`
- `commit()`

---

## ✅ Advantages

- Easy to understand and use
- Beginner-friendly project
- Permanent database storage
- Fast data retrieval
- Real-time database operations
- Demonstrates Python-MySQL integration

---

## ⚠️ Limitations

- Command-line interface only
- No login authentication
- No attendance management
- No fee management
- No report generation

---

## 🚀 Future Enhancements

- Login Authentication
- Student Attendance Module
- Fee Management System
- Result Analysis
- Export Records to Excel/PDF
- Search by Name or Course
- Update Complete Student Details
- GUI using Tkinter or PyQt
- Web Version using Flask or Django

---

## 🎯 Learning Outcomes

This project helped in understanding:

- Python and MySQL integration
- CRUD operations
- SQL query execution through Python
- Database transaction management
- Menu-driven application development
- Modular programming using functions

---

## 📌 Conclusion

The **Student Management System** is a simple yet effective database application developed using Python and MySQL. It successfully demonstrates CRUD operations, database connectivity, and structured programming concepts. The project serves as an excellent foundation for developing more advanced database-driven applications such as Employee Management Systems, Library Management Systems, and School ERP solutions.

---

## 👨‍💻 Author

**Sasi**

**Project:** Student Management System using Python & MySQL

---
