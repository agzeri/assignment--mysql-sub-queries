# MySQL Sub Queries

## The Assignment

Help your manager to extract data and format it using subqueries and MySQL functions. The exercises are below.

## Deliverables

+ a github repository named `assignment--mysql-sub-queries` with a `.sql` file containing all the queries.

###### Example

```sql
#1 Write a query to display all names from Products.

SELECT Id, Name
  FROM Products;
```

## Setup Instructions

1. Create assignment folder in terminal

  ```sh
  cd ~/muktek/assignments
  mkdir assignment--mysql-basic-queries

  curl  https://raw.githubusercontent.com/muktek/assignment--mysql-sub-queries/master/assignment-files/mysql-sub-queries.sql > mysql-sub-queries.sql
  ```

2. Connect to MySQL Server on [45.55.135.14/phpmyadmin](45.55.135.14/phpmyadmin) and create your a copy of the database under your name. NOTE: Format name of should be `HR_«your-github-name»`.

  ```sh
  ssh root@45.55.135.14
    # enter password when asked to
  ```


3. Inside mysql shell, connect to your HR_ database to complete the exercises (you should have one already from the previous exercise)
  ```sh
  mysql> mysql -u root -p
    # enter password when asked to

  # enter your database
  mysql> USE HR_yourGithubUsername
  ```

4. Check to see the tables are there

  ```sh
  mysql> SHOW TABLES;
  # =>
  +------------------------+
  | Tables_in_HR_scoobydoo |
  +------------------------+
  | Countries              |
  | Departments            |
  | Employees              |
  | JobHistory             |
  | Jobs                   |
  | Locations              |
  | Regions                |
  +------------------------+
  ```

4. You will need to write/record your queries in the `mysql-sub-queries.sql` file




## Exercise

```sql
# 1) Write a query to find the name (FIRST_NAME, LAST_NAME)
#  and salary of the employees who earn a salary that is higher than
#  the salary of all the Shipping Clerks (JOB_ID = 'SH_CLERK').
#  Sort the results of the salary of the lowest to highest. Employees

# 2) Write a query to find the name (FIRST_NAME, LAST_NAME) of the employees
#  who are not supervisors. Employees

# 3) Write a query to display the employee ID, first name, last name, and department names of all employees.
#    Employees, Departments

# 4) Write a query to display the employee ID, first name, last name, salary of all employees
#   whose salary is above average for their departments.
#   Employees, Departments

# 5) Write a query to fetch even numbered records from employees table. Employees

# 6) Write a query to find the 5th maximum salary in the employees table. Employees

# 7) Write a query to find the 4th minimum salary in the employees table. Employees

# 8) Write a query to select last 10 records from a table. Employees

# 9) Write a query to list the department ID and name of all the departments
#   where no employee is working. Employees, Departments

# 10) Write a query to get the 3 maximum salaries. Employees

# 11) Write a query to get the 3 minimum salaries. Employees
```
