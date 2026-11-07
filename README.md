# Spring JDBC Practice

A collection of Java Spring JDBC practice projects demonstrating database connectivity and database operations using Spring's JdbcTemplate.

This repository contains independent examples using both XML-based and Java-based Spring configuration, with MySQL as the database.

## Projects Included

### 1. Student Management – XML Configuration
- Configure Spring JDBC using XML.
- Configure DataSource and JdbcTemplate.
- Insert student records.
- Delete student records.
- Retrieve a student by ID.
- Retrieve all student records.

### 2. Student Management – Java Configuration
- Configure Spring using Java-based configuration.
- Define beans using `@Configuration` and `@Bean`.
- Perform database operations using JdbcTemplate.
- Implement RowMapper for mapping database records to Java objects.

### 3. Customer Management – XML Configuration
- Configure Spring JDBC using XML.
- Perform customer database operations.
- Insert and delete customer records.
- Retrieve customer details and customer lists.

### 4. Customer Management – Java Configuration
- Configure Spring JDBC using Java-based configuration.
- Define database-related beans.
- Implement DAO-based database operations.

## Concepts Covered

- Spring JDBC
- JdbcTemplate
- DataSource Configuration
- DAO Pattern
- RowMapper
- XML-Based Configuration
- Java-Based Configuration
- MySQL Database Connectivity
- Parameterized SQL Queries
- Basic Database Operations

## Technologies Used

- Java
- Spring Framework 6
- Spring JDBC
- MySQL
- Maven
- XML Configuration
- Java-Based Configuration
- Eclipse IDE

## Project Structure

```text
Spring-JDBC-Practice/
│
├── springJDBC/
│   └── Student Management using XML Configuration
│
├── springJDBCwithoutXML/
│   └── Student Management using Java Configuration
│
├── CRM_SpringJDBC_console/
│   └── Customer Management using XML Configuration
│
└── CRM_SpringJDBC_NoXML_Console/
    └── Customer Management using Java Configuration
```

## Prerequisites

- JDK 17 or later
- Apache Maven
- MySQL Server
- Eclipse IDE or another Java IDE

## Database Configuration

1. Create the required MySQL database.
2. Open the relevant Spring configuration file:
   - `config.xml` for XML-based configuration.
   - `ConfigureData.java` for Java-based configuration.
3. Configure the database URL, username, and password for your local environment.
4. Ensure the required tables are created before running the application.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Sunilmaske12/Spring-JDBC-Practice.git
   ```

2. Import the required project folder into Eclipse as an existing Maven project.

3. Update the MySQL database configuration.

4. Resolve Maven dependencies.

5. Run the appropriate Java main class.

## Learning Objectives

- Understand Spring JDBC integration.
- Perform database operations using JdbcTemplate.
- Implement DAO and RowMapper.
- Configure Spring using XML and Java configuration.
- Understand the interaction between Java objects and relational database records.

## Author

**Sunil Maske**

- GitHub: https://github.com/Sunilmaske12
- LinkedIn: https://www.linkedin.com/in/sunil-maske/
- LeetCode: https://leetcode.com/u/maskesunil16/
