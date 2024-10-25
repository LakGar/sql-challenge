# SQL Challenge: Employee Data Analysis

## Background

This project involves creating and analyzing an employee database for a fictional company, Pewlett Hackard. The task is to analyze employee data from the 1980s and 1990s using six provided CSV files. The project involves three main tasks: data modeling, data engineering, and data analysis.

## Project Overview

1. **Data Modeling**: Create an Entity Relationship Diagram (ERD) based on the CSV data to design the table structure.
2. **Data Engineering**: Create SQL tables based on the ERD, import the CSV files into the database, and ensure correct relationships using primary and foreign keys.
3. **Data Analysis**: Run SQL queries to answer specific business questions about employee data.

## Files and Structure

- **`data/`**: Contains the six CSV files with employee data.
- **`schema.sql`**: SQL file containing the table schema for all six tables.
- **`queries.sql`**: SQL file with the queries used to analyze the employee data.
- **`ERD.png`**: Entity Relationship Diagram of the database.
- **`README.md`**: This file, explaining the project and how to use it.

## Instructions

### Data Modeling

1. Inspect the provided CSV files.
2. Design an Entity Relationship Diagram (ERD) that represents the relationships between the tables.
3. Use a tool like QuickDBD to sketch the ERD and include it in the project as `ERD.png`.

### Data Engineering

1. **Create Table Schemas**:
   - Use the information from the CSV files to define the appropriate columns, data types, and constraints (e.g., `NOT NULL`, `PRIMARY KEY`, `FOREIGN KEY`).
   - Ensure the correct order of table creation to handle foreign key dependencies.
2. **Import Data**:
   - Import the data from the CSV files into the corresponding tables using SQL commands.
   - Make sure the data is inserted in the correct order to avoid issues with foreign key constraints.

### Data Analysis

Run the following SQL queries to answer the business questions:

1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (i.e., how many employees share each last name).

## Submission Requirements

Ensure the following files are included in your repository:

- **ERD**: An image of the Entity Relationship Diagram (`ERD.png`).
- **Table Schemas**: A `.sql` file (`schema.sql`) containing the schema definitions for all tables.
- **Queries**: A `.sql` file (`queries.sql`) containing the SQL queries used for data analysis.
- **README**: This `README.md` file explaining the project.
