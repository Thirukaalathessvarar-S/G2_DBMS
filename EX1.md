# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## DATE: 3/8/23

## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```
### OUTPUT:
![image](https://github.com/Thirukaalathessvarar-S/G2_DBMS/assets/121166390/5df62be6-e38c-49be-8fb0-b1b2e917ce11)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/Thirukaalathessvarar-S/G2_DBMS/assets/121166390/b019bffa-6e07-4b82-a2a6-dc309619f837)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:
![image](https://github.com/Thirukaalathessvarar-S/G2_DBMS/assets/121166390/89b017a9-ba94-4e99-8d58-8fb59efc2b16)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:
![image](https://github.com/Thirukaalathessvarar-S/G2_DBMS/assets/121166390/ed485b65-7a5d-4d5f-8251-61d39f155de6)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/Thirukaalathessvarar-S/G2_DBMS/assets/121166390/6bba799c-b16a-4005-9930-c1e22e090057)

## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
