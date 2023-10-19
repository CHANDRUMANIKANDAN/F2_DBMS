# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
```sql
create table student(rollno int,name varchar(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![exp 1](https://github.com/CHANDRUMANIKANDAN/F2_DBMS/assets/118644502/8ac437ea-1a27-40cd-82a4-61ab8082e94d)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student add(department varchar(20));
```
### OUTPUT:
![exp 1 2](https://github.com/CHANDRUMANIKANDAN/F2_DBMS/assets/118644502/e1f37c95-a260-4f91-9b6c-da7057cde228)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table student;
```
### OUTPUT:
![exp 1 3](https://github.com/CHANDRUMANIKANDAN/F2_DBMS/assets/118644502/da742793-da6f-4148-8985-c66877714023)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table student;
```
### OUTPUT:
![exp 1 4](https://github.com/CHANDRUMANIKANDAN/F2_DBMS/assets/118644502/d7dadeac-1a91-483b-89b8-28b240d15434)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student rename to myystudent;
```
### OUTPUT:
![exp1 5](https://github.com/CHANDRUMANIKANDAN/F2_DBMS/assets/118644502/b5c200f9-e718-4752-a1b6-83f852102982)
