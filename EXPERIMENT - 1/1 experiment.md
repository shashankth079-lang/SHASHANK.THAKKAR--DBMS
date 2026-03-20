📘 AIM

To perform SQL operations such as CREATE, DELETE, UPDATE, ALTER, and DROP on a table derived from the EMPLOYEE table.

📖 THEORY

SQL (Structured Query Language) is used to manage and manipulate relational databases.

CREATE TABLE → Creates a new table

INSERT INTO / SELECT INTO → Copies data

DELETE → Removes records

UPDATE → Modifies existing data

ALTER → Changes table structure

DROP → Deletes the table permanently


Perform following Query
1. Create Employee_master table with data using Employee
table.

Query:
CREATE TABLE Employee_Master AS
SELECT * FROM EMPLOYEE;
![alt text](12.png)

2. 3. Delete all record into Employee_master whose DeptNo is 10
Update 10% in his salary of DEPTNO 20 into
Employee_Master.
4. Alter SAL with size 10,2 in Employee_Master.
5. Drop Employee_master Table.