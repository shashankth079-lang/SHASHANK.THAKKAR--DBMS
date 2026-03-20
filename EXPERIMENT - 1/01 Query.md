✅ 1. Create Employee_Master table with data
Query:
CREATE TABLE Employee_Master AS
SELECT * FROM EMPLOYEE; 


✅ 2. Delete all records where DEPTNO = 10
Query:
DELETE FROM Employee_Master
WHERE DEPTNO = 10;


✅ 3. Update salary by 10% for DEPTNO = 20
Query:
UPDATE Employee_Master
SET SAL = SAL + (SAL * 0.10)
WHERE DEPTNO = 20;