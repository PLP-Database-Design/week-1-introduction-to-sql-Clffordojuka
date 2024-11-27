# Assignment Questions

State and Explain the components of a DBMS(Database Management System)

What is a relational database? Give 4 examples.

State and Explain three classifications of SQL?

What is the difference between a Primary Key and a Foreign Key?

What is an Entity-Relationship Diagram?

What are the advantages of relational databases?

State four types of data type used to store data in tables?

What is the purpose of a database management system (DBMS)?

# Answers to Assignment Questions

### Components of a Database Management System (DBMS)

1. **Database Engine**: 
   - Responsible for data storage, retrieval, and manipulation.
   - Ensures data consistency, integrity, and transaction handling.

2. **Database Schema**: 
   - Defines the structure of the database, including tables, fields, relationships, and constraints.

3. **Query Processor**: 
   - Interprets and executes database queries, usually written in SQL.
   - Optimizes queries for efficient execution.

4. **Transaction Management**: 
   - Ensures ACID properties (Atomicity, Consistency, Isolation, Durability) for reliable transaction processing.

5. **Data Storage Management**: 
   - Manages physical storage of data on disks or other media.

6. **Metadata Manager**: 
   - Manages information about the data (metadata), such as data types, relationships, and constraints.

7. **User Interface**: 
   - Provides tools for users or developers to interact with the database, including GUI or command-line interfaces.

---

### What is a Relational Database?
A **relational database** organizes data into tables (relations) with rows (records) and columns (fields). Data is stored in a structured format, and relationships between tables are defined using keys. It follows the principles of relational algebra.

**Examples**:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

---

### Three Classifications of SQL
1. **Data Definition Language (DDL)**:
   - Used to define or modify database structures.
   - Includes commands like `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.

2. **Data Manipulation Language (DML)**:
   - Used to retrieve, insert, update, and delete data.
   - Includes commands like `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

3. **Data Control Language (DCL)**:
   - Used to control access to data.
   - Includes commands like `GRANT`, `REVOKE`.

---

### Difference Between a Primary Key and a Foreign Key
- **Primary Key**:
  - Uniquely identifies each record in a table.
  - Cannot contain `NULL` values.
  - Example: `id` column in a `Users` table.

- **Foreign Key**:
  - Establishes a relationship between two tables by referencing the primary key in another table.
  - Can contain `NULL` values if not part of the relationship.
  - Example: `user_id` in an `Orders` table referencing `id` in the `Users` table.

---

### What is an Entity-Relationship Diagram?
An **Entity-Relationship Diagram (ERD)** visually represents the structure of a database. It illustrates entities (tables), attributes (columns), and relationships (links) between them. ERDs help in database design by clarifying the organization of data.

---

### Advantages of Relational Databases
1. **Data Integrity**: Enforces data consistency through constraints like primary and foreign keys.
2. **Flexibility**: Allows data to be added, updated, or queried without affecting overall structure.
3. **Scalability**: Can handle large datasets and complex queries efficiently.
4. **Standardized Language**: Uses SQL, a universally adopted query language.

---

### Four Types of Data Types to Store Data in Tables
1. **INTEGER**: Stores whole numbers (e.g., `age`, `count`).
2. **VARCHAR**: Stores variable-length strings (e.g., `name`, `email`).
3. **DATE**: Stores date values (e.g., `birth_date`, `hire_date`).
4. **BOOLEAN**: Stores true/false values (e.g., `is_active`).

---

### Purpose of a Database Management System (DBMS)
A **DBMS** provides a systematic way to manage, store, retrieve, and update data while ensuring data security, consistency, and integrity. Its purposes include:
- Enabling data access and manipulation using SQL.
- Managing transactions and concurrency.
- Supporting data backup and recovery.
- Providing multi-user access while maintaining security.

---

