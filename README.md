🎓 Student Management System using Python & MySQL
📌 Project Overview

The Student Management System is a menu-driven database application developed using Python and MySQL to efficiently manage student information. It enables users to perform essential database operations such as adding new student records, updating marks, searching for students, displaying all records, and deleting student information. The project demonstrates the integration of Python with MySQL using the mysql-connector-python library and follows the principles of CRUD (Create, Read, Update, Delete) operations.

The primary objective of this project is to automate student record management, eliminating the need for manual record keeping. It provides a simple and user-friendly interface that allows users to interact with the database through a command-line menu.

🚀 Features
Add new student records
Search students using Student ID
Update student marks
Display all student records
Delete student records
Menu-driven interface
Secure MySQL database storage
Fast data retrieval using SQL queries
🛠️ Technologies Used
Technology	Purpose
Python 3.x	Application Development
MySQL 8.0	Database Management
mysql-connector-python	Python-MySQL Connectivity
Jupyter Notebook	Development Environment
📂 Project Structure
Student_Management_System/
│
├── student_management.py
├── README.md
├── requirements.txt
├── student_management.sql
├── screenshots/
│     ├── menu.png
│     ├── add_student.png
│     ├── display_students.png
│     └── search_student.png
└── Project_Report.docx
📋 Database Schema
Create Database
CREATE DATABASE student_management;
Use Database
USE student_management;
Create Table
CREATE TABLE students(
    student_id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    gender VARCHAR(10),
    course VARCHAR(50),
    mobile VARCHAR(20),
    marks FLOAT
);
💻 Python Modules Used
import mysql.connector

The project uses the mysql-connector-python package to establish communication between Python and MySQL.

⚙️ Installation Guide
Step 1

Install Python 3.x

Download:
https://www.python.org/downloads/

Step 2

Install MySQL Community Server

Download:
https://dev.mysql.com/downloads/mysql/

Step 3

Install MySQL Workbench

Download:
https://dev.mysql.com/downloads/workbench/

Step 4

Install MySQL Connector

Open Command Prompt and run:

pip install mysql-connector-python
Step 5

Create the database and students table using the SQL script.

Step 6

Update your MySQL credentials inside the Python program.

mydb = mysql.connector.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="student_management"
)
▶️ How to Run the Project

Open Jupyter Notebook or VS Code.

Run the Python program.

The following menu will appear:

========== STUDENT MANAGEMENT SYSTEM ==========

1. Add Student
2. Update Marks
3. Search Student
4. Display All Students
5. Delete Student
6. Exit

Choose any option by entering the corresponding number.

📖 Functional Modules
1️⃣ Add Student

Allows users to add a new student record to the database.

Inputs:

Student ID
Name
Age
Gender
Course
Mobile Number
Marks
2️⃣ Update Marks

Updates the marks of an existing student using the Student ID.

3️⃣ Search Student

Searches and displays complete student details using the Student ID.

4️⃣ Display All Students

Retrieves and displays all student records stored in the MySQL database.

5️⃣ Delete Student

Deletes a student record permanently from the database using the Student ID.

6️⃣ Exit

Safely closes the database connection and exits the application.

🗃 Sample Student Record
Student ID	Name	Age	Gender	Course	Mobile	Marks
107	P. Sasi Kumar	21	Male	ECE	6300451881	94
🔄 CRUD Operations Used
Operation	SQL Command
Create	INSERT
Read	SELECT
Update	UPDATE
Delete	DELETE
🧠 Concepts Demonstrated
Python Functions
Conditional Statements (if-elif-else)
Loops (while)
User Input
SQL Queries
Database Connectivity
CRUD Operations
MySQL Commit Operations
Cursor Object
Data Retrieval using fetchone() and fetchall()
📈 Advantages
Easy to use
Beginner-friendly
Reduces manual record maintenance
Fast and accurate data retrieval
Permanent database storage
Demonstrates real-world database connectivity
Modular and easy-to-understand code structure
⚠️ Limitations
Command-line interface only
No user authentication
No attendance management
No fee management
No report generation
No backup or restore functionality
🚀 Future Enhancements

The project can be extended by adding:

Student Login & Admin Login
Attendance Management System
Fee Management Module
Result Analysis
Grade Calculation
Student Photo Storage
Export Student Data to Excel/PDF
Search Students by Name or Course
Update Complete Student Details
Graphical User Interface (Tkinter/PyQt)
Web-based Application using Flask or Django
🎯 Learning Outcomes

After completing this project, you will understand:

How to connect Python with MySQL
How CRUD applications work
How SQL queries are executed from Python
Database transaction management using commit()
Retrieving records using fetchone() and fetchall()
Designing menu-driven applications
Structuring Python code using functions
📚 Conclusion

The Student Management System is a practical Python-MySQL application that demonstrates how a programming language can interact with a relational database to manage information efficiently. The project successfully performs all CRUD operations while providing a simple, menu-driven interface for users. It serves as an excellent beginner-level database project and builds a strong foundation for developing larger applications such as Library Management Systems, Hospital Management Systems, Employee Management Systems, and School ERP solutions.

👨‍💻 Author

Sasi
Project: Student Management System using Python & MySQL
Language: Python
Database: MySQL
IDE: Jupyter Notebook
