# Data
Database creation
If you mean how to create a database, here are the simple steps, especially using SQL/MySQL.

Steps to create a database

1. Open your database software
For example, open MySQL Workbench, XAMPP/phpMyAdmin, or another SQL program.

2. Create the database

CREATE DATABASE School;

This creates a database called School.

3. Select the database

USE School;

This tells SQL that you want to work inside the School database.

4. Create a table

For example, a table for students:

CREATE TABLE Students (
    StudentID INT PRIMARY KEY,
    Name VARCHAR(50),
    Age INT,
    Course VARCHAR(50)
);

5. Add data to the table

INSERT INTO Students (StudentID, Name, Age, Course)
VALUES (1, 'Shilla', 20, 'Computer Science');

6. View the data

SELECT * FROM Students;
Simple meaning

Database → Tables → Columns → Records

For example:

StudentID	Name	Age	Course
1	Shilla	20	Computer Science
2	John	21	IT
Database: stores related information.
Table: organizes the information.
Column: describes the type of information, such as Name or Age.
Record/Row: contains information about one person or item.
Primary key: uniquely identifies each record.
