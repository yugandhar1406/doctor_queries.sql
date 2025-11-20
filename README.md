# Doctor Database SQL Queries

This project contains simple and clean SQL queries based on a sample `doctor` table.

## Table Structure
- id (int, primary key)
- first_name (varchar)
- last_name (varchar)
- email (varchar)
- specialization (varchar)

## Queries Included

###  Doctors named Mark with last name starting with D
SELECT last_name, specialization
FROM doctor
WHERE first_name = 'Mark' AND last_name LIKE 'D%';
