# SQL Basics – Database & Table Operations

This project demonstrates basic SQL operations like creating a database, creating tables, inserting data, and retrieving records.

## Features
- Create and delete a database
- Create a table
- Insert data into table
- Retrieve data using SELECT

## SQL Commands

### Create Database
CREATE DATABASE gita;

### Use Database
USE gita;

### Delete Database
DROP DATABASE gita;

### Create Table
CREATE TABLE student (
  Roll_no INT,
  Name VARCHAR(50),
  Age INT
);

### Insert Data
INSERT INTO student 
VALUES (66, "SOUBHAGYA", 20);

### Display Data
SELECT * FROM student;

## Data Types Used

- INT → Integer values  
- VARCHAR(n) → Variable length string  
- CHAR(n) → Fixed length string  
- FLOAT / DOUBLE → Decimal numbers  
- BOOLEAN → True/False  
- DATE → Format YYYY-MM-DD  

## Notes
- SQL is case-insensitive
- Use uppercase for better readability
- Always end statements with semicolon (;)
