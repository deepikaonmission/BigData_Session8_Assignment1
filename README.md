# BigData_Session8_Assignment1

NOTE:
1. In order to use hive, start all hadoop daemons using "start-all" command, and strat mysqld service using "sudo servie mysqld start"
2. Then, Launch hive using "hive" command

For Assignment 8.1, following screenshots are associated:

-> Screenshots 1-7 describe
* creation of emp_with_salary table inside emp database
* loading data inside emp_with_salary table

-> Below Screenshots provide required solutions for the asked queries:

<<<<<<<<<<<------------- QUERY 1 --------------->>>>>>>>>>>>>
"Get a list of employees who receive a salary less than 100, compared to their immediate employee with higher salary in the same unit"

REFER Screenshots: Query1.1.JPG and Query1.2.JPG

<<<<<<<<<<<------------- QUERY 2 --------------->>>>>>>>>>>>>
"List of all employees who draw higher salary than the average salary of that department"

REFER Screenshots: 
Query2.1.JPG and Query2.2.JPG (with fields: id,name,salary,dept)
OR
Query2.3.JPG and Query2.4.JPG (with fields: id,name,salary,dept,avg(salary))   --->> gives more clarification
