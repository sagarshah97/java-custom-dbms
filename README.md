# Custom DBMS - Console-Based Application for Database Operations with Enhanced Security

This project is a powerful Java console-based SQL query execution programme that supports user interaction and database management. It offers a complete two-factor authentication module that makes use of user ID, password, and security questions and answers for improved login security. It also ensures support for many users through the authentication system and uses a common Java library (like md5) for safe password hashing. It employs a unique file format for persistently storing data, user information, and logs, doing away with the need for standard formats like JSON, XML, or CSV by utilizing cutting-edge delimiters to facilitate effective data storage and retrieval within a text file, showcasing ingenuity in file management techniques. The data at rest in files, is also encrypted along with the delimiters which makes it more secure and cannot be accessed with this application.

## IDE Information

- This application has been developed using `VSCode` as the IDE
- A basic Java project was selected as the template to start this project
- The two folders were generated by default: `src` and `bin`

## Java Information

- Java Version: `19.0.1`

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `bin`: the folder to maintain class files

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

## General Information

- `App.java` is the default app which will run and call the subsequent classes and methods.
- All the generated files via code, will be stored in the rot directory.

## Sample SQL Queries and types

> CREATE DATABASE

- `CREATE DATABASE personDb;`

> CREATE TABLE

- `CREATE TABLE Persons (ID int NOT NULL, LastName varchar(255) NOT NULL, FirstName varchar(255) NULL, Age int, PRIMARY KEY (ID));`

> INSERT

- `INSERT INTO persons VALUES (1, 'Doe', 'John', 25);`

- `INSERT INTO persons (Id, Lastname, Firstname, Age) VALUES (1, 'Doe', 'Jane', 25);`

> SELECT

- `SELECT * FROM persons;`

- `SELECT id, firstname, lastname FROM persons;`

> UPDATE

- `UPDATE persons SET lastname = "Smith", age = 60 WHERE id=1;`

> DELETE

- `DELETE FROM persons WHERE id=1;`

> TRUNCATE

- `TRUNCATE TABLE persons;`

> DROP TABLE

- `DROP TABLE persons;`

> DROP DATABASE

- `DROP DATABASE personDb;`
