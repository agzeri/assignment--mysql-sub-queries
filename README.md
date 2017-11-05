# MySQL Sub Queries

## The Assignment

Help your manager to extract data and format it using subqueries and MySQL functions.

## Deliverables

  + a github repository named `assignment--mysql-sub-queries`

## Setup Instructions

  1. Connect to MySQL Server on [45.55.135.14/phpmyadmin](45.55.135.14/phpmyadmin)
  2. Copy the `HR` database and add your initial letters as suffix.

  ###### Example
  
  ```sql
  CREATE DATABASE HR_BG; # Bill Gates
  ```

## Exercise

```sql
#1 Write a query to find the name (FIRST_NAME, LAST_NAME) and salary of the employees who earn a salary that is higher than the salary of all the Shipping Clerk (JOB_ID = 'SH_CLERK'). Sort the results of the salary of the lowest to highest. Employees

#2 Write a query to find the name (FIRST_NAME, LAST_NAME) of the employees who are not supervisors. Employees

#3 Write a query to display the employee ID, first name, last name, and department names of all employees. Employees, Departments

#4 Write a query to display the employee ID, first name, last name, salary of all employees whose salary is above average for their departments. Employees, Departments

#5 Write a query to fetch even numbered records from employees table. Employees

#6 Write a query to find the 5th maximum salary in the employees table. Employees

#7 Write a query to find the 4th minimum salary in the employees table. Employees

#8 Write a query to select last 10 records from a table. Employees

#9 Write a query to list the department ID and name of all the departments where no employee is working. Employees, Departments

#10 Write a query to get 3 maximum salaries. Employees

#11 Write a query to get 3 minimum salaries. Employees
```
