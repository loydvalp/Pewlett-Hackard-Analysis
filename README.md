# Pewlett-Hackard-Analysis

## Project Challenge Overview

Pewlett Hackard is a large company boasting thousand employees.  The baby boomers of he company are getting ready to retire.  PH is offering retirement package for those who mee cetain criteria.  Also, it is looking ino which position needs to be filled.  HR Analyst tasked is to perform employee research to specifically answer the questions who will be retiring and how many positions needs to be filled. 

HR analyst manager has given two more assignments: determine the total number of employees per title who will be retiring, and identify employeees who are eligible to participate in a mentorship program.  

## Resouces
- Data Soucres: department.csv, dept_emp.csv, employees.csv, dept_manager.csv, salaries.csv, titles.csv
- Softward: PostgreSQL: pgAdmin4, Quick DBD

## Technical Analyis Deliverable 1:

1. For this analysis, create a table containing the number of employees who are about to retire (those born 1952-1955), grouped by job title. Using your ERD as a reference, create this table with an inner join. Your table will contain the following information:

  - Employee number
  - First and last name
  - Title
  - from_date
  - Salary

2.  Query the new table using the SELECT statement. You want to see all columns and rows, so select everything. Create a new table that includes only the most recent title of each employee

3.  Need to use the code provided below to complete the partition portion of the query. Create table.

## Technical Analyis Deliverable 2:

1.  For this table, you will need to include the following information:

  - Employee number
  - First and last name
  - Title
  - from_date and to_date

To be eligible to participate in the mentorship program, employees will need to have a date of birth that falls between January 1, 1965 and December 31, 1965. Create Table.

## Summary

The problem identified was determing how many employees will be retiring soon and what were their titles in the departments.  The only data was available was 6 csv files.  The first thing was to build an  Entity Relationship Diagram (ERD) to understand the relationship between each data by finding what connects them together.  The data was connected through primary keys (unique values in the main table) and foreign keys (unique values in other tables.  See the ERD of Pewlett Harkard Employee below:

![](EmployeeeDB_ERD.png)

Once the relationship of the database was created, I added the data into a PostgresSQL database.  In SQL, I created muliple tables by connecting the primary key and foreign keys gain relevant information from the multiple tables. 

