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
```
create table student101(roll_no int,name varchar(30),age int,address varchar(50),phone_no int);
```

### OUTPUT:
![dbmstable1](https://github.com/ASHWINKUMAR2903/I2_DBMS/assets/119407186/bd4cc76c-ac53-416e-8667-2e589f5bb8a7)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student101 add department varchar(30);
```

### OUTPUT:
![dbmstable2](https://github.com/ASHWINKUMAR2903/I2_DBMS/assets/119407186/d57586fd-3cec-4f02-b6e0-b8d9ac24a10f)


### 3) Rename the student table to mystudent

### SQL QUERY: 
```
 alter table student101 rename to student202;
```
### OUTPUT:
![dbmstable3](https://github.com/ASHWINKUMAR2903/I2_DBMS/assets/119407186/9a9de3d3-3093-417d-acf3-f20b572531b7)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student202;
```
### OUTPUT:
![dbmstable4](https://github.com/ASHWINKUMAR2903/I2_DBMS/assets/119407186/d0a19bfe-8951-481b-92b3-08b132f60f68)



### 5) Drop the student table
 
### SQL QUERY: 
```
drop table student202;
```
### OUTPUT:
![dbmstable5](https://github.com/ASHWINKUMAR2903/I2_DBMS/assets/119407186/4f4e6a54-2b84-46b2-aa04-b02fe25a1c19)

## RESULT:
the SQL Command is executed successfully. 

