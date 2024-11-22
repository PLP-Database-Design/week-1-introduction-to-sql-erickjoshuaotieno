### State and Explain the Components of a DBMS (Database Management System)

A DBMS is a software system that enables users to define, create, and manage databases. Its components include:

- Database Engine: Performs CRUD operations (Create, Read, Update, Delete) on the database.
- Database Schema: Defines the structure of the data, including tables, relationships, and constraints.
- Query Processor: Interprets and executes database queries written in SQL.
- Transaction Management: Ensures data consistency during concurrent access or system failures using ACID properties.
- Data Storage Manager: Handles data storage on physical devices and retrieves it efficiently.
- Database Administration Tools: Provide functionalities for managing users, security, and backups.

### What is a Relational Database? Give 4 Examples.

A relational database organizes data into structured tables (relations) with rows and columns. Relationships between tables are established using keys.

Examples include:

- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server

### State and Explain Three Classifications of SQL

Data Definition Language (DDL): Used to define database structures, such as creating or modifying tables.
Examples: CREATE, ALTER, DROP

Data Manipulation Language (DML): Handles data manipulation within tables.
Examples: SELECT, INSERT, UPDATE, DELETE

Data Control Language (DCL): Manages access control and permissions.
Examples: GRANT, REVOKE

### What is the Difference Between a Primary Key and a Foreign Key?

- Primary Key: A unique identifier for each row in a table. No two rows can have the same primary key value. Example: student_id in a students table.

- Foreign Key: A column in a table that establishes a relationship with the primary key of another table. Example: course_id in an enrollments table referencing the course_id in a courses table.


### What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of the database's structure. It uses symbols to depict:

- Entities: Objects or concepts (e.g., Students, Courses)
- Attributes: Characteristics of entities (e.g., Name, Age)
- Relationships: Associations between entities (e.g., Enrolls in).

ERDs help in planning and designing databases.

###  What Are the Advantages of Relational Databases?

- Data Integrity: Ensures accuracy and consistency using constraints like primary and foreign keys.
- Flexibility: Easily scalable and modifiable to accommodate new data types or relationships.
- Security: Allows user access control and permissions for secure data management.
- Ease of Querying: SQL provides a straightforward way to manipulate and retrieve data.

### State Four Types of Data Types Used to Store Data in Tables

- Integer (INT): Stores whole numbers.
- Character/String (VARCHAR, CHAR): Stores text.
- Date/Time (DATE, DATETIME): Stores date and time values.
- Decimal (DECIMAL, FLOAT): Stores fractional numbers or monetary values.

### What is the Purpose of a Database Management System (DBMS)?

The purpose of a DBMS is to:

- Efficiently Manage Data: Store, retrieve, and update data systematically.
- Ensure Data Integrity: Maintain consistency and correctness.
- Provide Security: Control user access and permissions.
- Support Multi-User Access: Allow concurrent data access while avoiding conflicts.
- Facilitate Query Execution: Simplify complex operations through SQL commands.
