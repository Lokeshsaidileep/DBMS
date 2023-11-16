# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a database studentdb

### SQL QUERY:
```
Create database studentdb;
```
### OUTPUT:
![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/5968202e-2181-4492-9795-14088ac07bb7)

### 2) Create a table student with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY: 
```
 create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
```

### OUTPUT:
![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/a475cc2c-991e-42d0-be06-760cd909cb7c)

### 3) Alter the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/04623f48-4711-485a-9758-8251a8e292ed)


### 4) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:
![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/0d1a229b-1a17-4a59-999d-89f6d9bf9d96)


### 5) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:

![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/a7ebfb1a-a69a-48c0-9aa3-76730edc2e5f)


### 6) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:
![image](https://github.com/Adithya-Siddam/DBMS/assets/93427248/8586ae53-a448-4913-814e-ee695781ecfd)


## Result:
         Thus the basic DDL commands in SQL are executed. 
