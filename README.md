# Taxi-service

This is a web application to show simple CRUD operations, authentication, and registration using MySQL and servlets, without any frameworks.

### Functionality
- Register a driver
- Log in and log out
- CRUD operation with drivers
- CRUD operation with cars
- CRUD operation with the manufacturer
- Show all driver cars
- Show all drivers
- Show all manufacturer
- Show all cars

### Project structure
- Data Access Object layer (DAO) - layer for work with database.
- Service layer - layer for business logic (sending queries to the database).
- Controller layer - layer of presentation of the user interface (sending requests to the service).

### Technology

- Java 11
- Tomcat 9.0.76
- MySQL 8.0.22
- Maven 3.1.1
- Java Servlet 4.0.1
- JSTL 1.2
- JSP, CSS
- JDBC

### Instruction for launching the project
1. Fork this project for your repository
2. Clone the project from your repository to IDEA using the code button and choosing the option you need
3. Install MySQL and Apache Tomcat version: 9.0.76 (if you need)
4. Create a database using either a local MySQL installation or a remote database. 
Execute the schema provided in the init_db.sql file to set up the necessary tables and structure for the project.
5. Open the project in your preferred IDE. Locate the ConnectionUtil class in package util in the project. It should contain the database connection settings. Fill in the appropriate values for the following fields:
![img.png](img.png)
6. Set up the configuration for Tomcat:
![img_1.png](img_1.png)
7. Copy and run SQL script from resources/init_db.sql in order to create a schema and tables for the project 
8. After starting Tomcat, you will be able to access your application by the URL
