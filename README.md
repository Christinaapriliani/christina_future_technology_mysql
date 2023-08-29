# Christina Future Technology MySQL Mini Project

This MySQL mini project demonstrates the creation of a more complex database structure for managing employee information, departments, projects, and salaries in the fictional company "Christina Future Technology."

## Table of Contents

- [Project Structure](#project-structure)
- [Database Schema](#database-schema)
- [Queries](#queries)
- [Usage](#usage)
- [License](#license)

## Project Structure

christina_future_technology_mysql/
├── create_tables.sql
├── insert_data.sql
├── complex_queries.sql
└── README.md

- `create_tables.sql`: Contains SQL statements to create the necessary tables (`Employees`, `Departments`, `Projects`, and `EmployeeProjects`).
- `insert_data.sql`: Contains SQL statements to insert sample data into the tables.
- `complex_queries.sql`: Contains complex SQL queries to retrieve useful insights from the database.
- `README.md`: This file, providing an overview of the project.

## Database Schema

The database consists of the following tables:

- `Employees`: Stores employee information including their ID, first name, last name, department, and salary.
- `Departments`: Stores department information including department ID and name.
- `Projects`: Stores project information including project ID, project name, and department.
- `EmployeeProjects`: Maps employees to projects they are involved in.

## Queries

The `complex_queries.sql` file contains several complex SQL queries to demonstrate the following:

1. Display a list of employees with their associated department, projects, and salaries.
2. Show the total salary paid in each department.
3. List employees with the highest salary in each department.

## Usage

1. Ensure you have a MySQL database environment set up.
2. Execute `create_tables.sql` to create the necessary tables.
3. Execute `insert_data.sql` to insert sample data.
4. Run the queries in `complex_queries.sql` to retrieve insights from the database.

## License

This project is licensed under CHRISTINA License. Feel free to u