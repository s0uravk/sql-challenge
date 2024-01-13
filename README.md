# sql-challenge
![SQL2](https://github.com/s0uravk/sql-challenge/assets/144293972/db71b72b-b38e-4dec-a766-dc62d219689e)

This sql-challenge works with 6 csv files for an employee database where it Entity relationship diagram is created based on the columns in each csv file and then converted into schema for the database. After creating the schema, csv files are imported and then required data was shown using SQL queries.

To begin with, employees table is created with emp_no as primary key and emp_title_id as foreign key, which is the primary key in titles table. Then salaries table has emp_no as foreign key, connecting it to employees table using many to one relationship. Furthermore, departments table is created with dept_no as primary keys and connects to dept_emp and dept_manager using dept_no with one to many relationship, and then both these tables connects to employees table using emp_no with many to one relationship.

As we have all the tables connected, schema is imported for postgres sql server. Then, EmployeeSQL database is created and schema file is executed to create the tables. Next step is to import the csv files into there corresponding tables in a specific order, importing tables with primary keys first i.e. titles, employees, salaries, departments, dept_manager, dept_emp.

After the import, we have data in our database and ready to perform some queries to get desired data. These SQL queries includes the use of statements such as SELECT, FROM, WHERE, JOINS, ILIKE, AND, OR, GROUP BY, ORDER BY and COUNT.
