# sql-challenge

This project involves setting up an employee database using PostgreSQL and conducting a series of data analysis tasks. 

The following tables are included:

- `departments`: Contains department information.
- `dept_emp`: Lists department and employee relationships.
- `dept_manager`: Lists which employees manage each department.
- `employees`: Contains employee information.
- `salaries`: Lists employee salaries.
- `titles`: Contains titles associated with each employee.

##Images

Review the images folder for screenshots of each sql query as listed below.

##Data Modeling

Data Modeling was created using QuickDBD and exported as PNG file in the EmployeeSQL folder in my local and pushed into the github.
##Data Engineering

All columns have their primary keys set, tables correctly related assigned with Foreign Keys, and Not Null conditions. 

Once the database is set up, the following analyses were performed using SQL queries:

1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).