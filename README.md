# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date: 04/08/2023

## AIM:

To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)

DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
## List of DDL commands:

CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY:
```
create table student(rollno char(5), name varchar(20), age char(5), address varchar(100), phoneno char(15));

```
### OUTPUT:

![image](https://github.com/Safeeq-Fazil/G2_DBMS/assets/118680361/d198b490-1795-4710-bb3e-e8f58b754c03)

### 2) Change the above student table by adding another attribute department

### SQL QUERY:

```
ALTER TABLE student
ADD department varchar(30);

```
### OUTPUT:

![image](https://github.com/Safeeq-Fazil/G2_DBMS/assets/118680361/cd8bcaf2-d997-4e9a-85fe-8af6ba84af07)

### 3) Drop the student table

### SQL QUERY:

```

drop table student;

```

### OUTPUT

![image](https://github.com/Safeeq-Fazil/G2_DBMS/assets/118680361/3b42d688-d2ca-4667-8545-f81383c6fb92)

### 4) Delete the student table using truncate keyword

### SQL QUERY:

```
truncate table student;
```

### OUTPUT:

![image](https://github.com/Safeeq-Fazil/G2_DBMS/assets/118680361/f7e452a1-c0a9-4087-8e55-911adb0ea481)

### 5) Rename the student table to mystudent

### SQL QUERY:
```
alter table student
rename to mystudent;

```
### OUTPUT:

![image](https://github.com/Safeeq-Fazil/G2_DBMS/assets/118680361/855fc107-aaa9-463c-9597-9389e1e35c85)

### RESULT:

Hence successfully created a student database and execute DDL queries using SQL.
