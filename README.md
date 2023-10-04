# Ex-No-4-Creating-Procedures-using-PL-SQL
# AIM : 
To create a procedure using PQ/SQL.
# STEPS
1)Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER); 2)Create a procedure named as insert_employee data. 3)Inside the procdure block, write the query for inserting the values into the employee table. 4)End the procedure. 5)Call the insert_employee data procedure to insert the values into the employee table. 6)Display the employee table
# PROGRAM
CREATE TABLE
~~~
create table employeetable1(id int,name char(20),dept char(20),salary int);
~~~
CREATE PROCEDURE
~~~
create or replace procedure insert_employeetable1_data AS
BEGIN
INSERT INTO employeetable1(id,name,dept,salary)
values (1,'john','HR',50000);
INSERT INTO employeetable1(id,name,dept,salary)
values (2,'joe','IT',60000);
INSERT INTO employeetable1(id,name,dept,salary)
values (3,'Bob','Finance',55000);
COMMIT;
END;
/
~~~
CALL PROCEDURE
~~~
begin
insert_employeetable1_data;
end;
/
~~~
DISPLAY TABLE
~~~
select * from employeetable1;
~~~
# OUTPUT
CREATE TABLE:

![5](https://github.com/21005984/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/94748389/16bef0a4-b247-4e78-9eff-fd899f3f581f)

CREATE PROCEDURE:

![6](https://github.com/21005984/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/94748389/ff8f048c-da44-40e9-b71e-0e799207ea05)

CALL PROCEDURE:

![7](https://github.com/21005984/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/94748389/f5001a5a-7830-47b3-8a1d-abf896ac02c1)

DISPLAY TABLE:

![8](https://github.com/21005984/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/94748389/ef149411-281c-4e29-abeb-6f13743c0521)

# RESULT:
Thus, a procedure is created successfully by using PL/SQL.







