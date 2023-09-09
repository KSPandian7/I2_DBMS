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
CREATE TABLE students(rollno INT,name VARCHAR(100),age INT,address VARCHAR(100),phoneno VARCHAR(15));
```


### OUTPUT:
![OUTPUT](![image](https://github.com/KSPandian7/I2_DBMS/assets/113496887/a0ee9a57-820a-4499-9c5a-dbe2c965f3ca)
)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
INSERT INTO students(rollno, name, age, address, phoneno) VALUES (1, 'John', 20, 'CHENNAI', '9153657854');
INSERT INTO students(rollno, name, age, address, phoneno) VALUES (2, 'SMITH', 25, 'TRICHY', '9746441548');
```

### OUTPUT:
![output](![image](https://github.com/KSPandian7/I2_DBMS/assets/113496887/809d00fc-daf3-43d1-90ff-870322e7b283)
)

### 3) Drop the student table
 
### SQL QUERY: 
```
DROP TABLE mystudent;
```

### OUTPUT:
![OUTPUT](![image](https://github.com/KSPandian7/I2_DBMS/assets/113496887/b32c2399-3ec2-40e9-8772-8a76786dbe97)
)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
TRUNCATE TABLE mystudent;
```
### OUTPUT:
![OUTPUT](![image](https://github.com/KSPandian7/I2_DBMS/assets/113496887/f738cc7a-73f0-4340-86e3-c1b8d0c15d62)
)


### 5) Rename the student table to mystudent

### SQL QUERY: 
```
ALTER TABLE students RENAME TO mystudent;
```


### OUTPUT:
![output](![image](https://github.com/KSPandian7/I2_DBMS/assets/113496887/82cd6b33-c26b-4dbb-b775-e21bfe5ff25a)
)
