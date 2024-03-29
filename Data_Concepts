# Data Concepts
---
## Structured data
- This refers to data organized in a perdictable format, making it easily searchable, sortable, and analyzable by machines.
- This type of data is typically organized into rows and columns (*similar to a table in a database*).
- The main characteristics of structured data include: **Organization** (*a predifined schema*), **Consistent format**, **Accessibile/Navigable**, **Scalability** (*scale to large volumes of data*), & **Relational**.

## Semi-structured data
- This refers to data that doesn't fit a traditional structured format but retains some level of organization.
- This type of data has a more flexible structure, allowing for variation in how the data is organized (*a mix between structured and unstructured data*).
- The main characteristics of semi-structured data include: **Flexibility** (*how data is organized & represented*), **Partial Organization** (*lacks consistancy*), **Self-description** (*can contain tags or metadata*), & **Format Variety** (*XML files, JSON, YAML*).

## Unstructure data
- This refers to data that doesn't have a predifined format or organization. 
- This type of data is essentially raw data that hasn't been organized into a structured format like a table or database.
- The main characteristics of unstructured data include: **Lack of Structure**, **Human-generated**, (*raw data, text docs, social media posts etc*), & **Varability** (*data varies in terms of content, size, and complexity*).

## Structured Query Language(SQL)
- This is a powerful programming language used to communicate with and manage databases, typically used to refer to any relational database. SQL is mostly used for : 
- **Database Manipulation** = to perform various operations on the data stored in database; INSERT,UPDATE,DELETE,SELECT,WHERE. 
- **Database Management** = to manage data stored in relational database management systems; create,modify,and delete tables & data within them.
- **Data Definition** = to create new databases, define tables with columns & data types.
- **Data Control** = to control access to the databases and content.
- **Data Transactions** = to commit or roll back a sequence of database operations that are treated as a single unit of work.

## ACID
- This acroynm refers to a set of 4 key properties that define a transaction:
- **Atomicity** = Each transaction is treated as a single unit of work; either all operations within the transaction are successfully completed, or none are leaving database unaffected (*if any part of transaction fails, entire transaction is rolled back to intial state*).
- **Consistency** = Ensuring database follows all defined rules & constraints, maintaining data intergity at all times (*if transaction violates any rules then it's aborted & DB reverts to its previous consistent state*).
- **Isolation** = Ensuring multiple transactions can operate simultaneously without interfering with each other (*each transaction running on system are isolated from one another*).
- **Durability** = Ensuring that once a transaction is committed, its changes remain permanent and can't be undone (*even in an event of a system crash or failure*).

## CRUD
- This acroynm refers to the 4 basic operations that can be performed on data within a database management system.
- **Create** = This operations involves adding new data or records (*a collection of data*) to a database.
- **Read** = This operation involves retrieving/accessing existing data from a database.
- **Update** = This operation involves modifiying existing data or records in a database.
- **Delete** = This operation involves removing existing data or record from a database.

## Online Transaction Processing(OLTP)
- This is a type of system that handles and manages transactions quickly and accurately in real-time (*like a super-efficient cashier*).
- OLTP systems are designed to effeciently process a large number of short, interactive transactions, such as INSERT, UPDATE, DELETE,and SELECT operations, performed by multiple users simultaneously.
- The main characteristics of OLTP systems include: **Real-time processing**, **Transactional Integrity** (*all transactions are done accurately & correctly*), **Handle Multiple Users**, **Optimized Read & Write Operations**, & **Normalized Data Structure** (*all data is organized*).

## Online Analytical Processing(OLAP)
- This is a type of system and technique used to analyze and query large volumes of data.
- OLAP systems are designed for complex analysis and reporting tasks, such as trend analysis, data mining and decicion-making support.
- The main characteristics of OLAP systems include: **Big Picture Analysis** (*aid to see the big picture by viewing lots of data all at once*), **Flexible Analysis** (*aids users to disect/slice data in various ways to anaalyze it from different angles*), **Support Decision Making**, **Group/Aggregate Data** (*group data together to make it easier to understand*), & **Interactive Tools** (*aids to interact with data & explore it*).

## Relational Database Management System(RDMS)
- This is a software system that helps store, manage, and retrieve data in a structured/organized manner.
- RDBMS allow to establish relationships between different tables.

## Not Only SQL(NoSQL)
- This is an alternative type of database management system from RDBMS.
- NoSQL databases are designed to handle large & diverse volumes of unstructured, semi-structured, or rapid changing data more effeciently, typically used for any non-realtional databases.

## Client drivers (JDBC, ODBC)
- These drivers are software components that facilitate communication between computer programs --> databases, allowing them to storer and retrieve data as needed.
- They act as a bridge, making it easier for developers to build applications that work with databases seamlessly.
- **Java Database Connectivity(JDBC)**: This is a Java API that enables java programs/apps connect and interact with relational databases (*provides interfaces for java programs to connect to DBs, execute SQL queries, retrieve, manipulate data, and manage database transactions*);
- JDBC drivers are implemented in Java and are available for various DB systems, such as MySQL, OracleSQL, PostgreSQL etc.
- **Open Database Connectivity(ODBC)**: This is a standard API for accessing databases develpoed by Microsoft (*provides a common interface for client apps/programs written in various programming languages, such as Python, C, C++, to connect to databases and perform operations*);
- ODBC drivers are available for a wide range of database systems & platforms, allowing apps to access different DBs using a unified API.

## Data backup and replication
- **Data Backup** involves creating copies of your data and storing them in a seperate location or different storage media, the purpose of backups is to protect against data loss in the event of hardware failure, software errors etc;
- Backups are used to restore the data back to its original state, minimizing downtime and disruption to operations.
- **Data Replication** involves creating and maintaining duplicate copies of data in real-time or near-real-time across multiple storage systems or locations, the purpose of replication is to improve data availability, resilience, and performance, ensuring data is accessible from multiple sources;
- Replication can be synchronous (*immediate replication to secondary location*), or asynchronous (*delayed replication*).

## Strong Consistency
- This refers to a guarantee provided by distributed systems that whenever data is updated or modified, all subsquent reads to that data will reflect the most recent update.
- Ensures all nodes see the same data updates at the same time.

## Eventual Consistency
- This refers to a consistency model used in distributed systems that data updates may take some time to propagate and communicate across all nodes in the system.
- Ensures a temporary period where different nodes have slightly different views of the data, eventually all nodes have the same data.

## Schema
- This refers to a blueprint or plan that defines the structure, organization, and format of data within a database.
- It essentially outlines how the data is organized, types of data allowed, and sets any rules or constrainst that govern the data.

## Table
- This refers to a data structure used in relational databases to organize, store, and manage data in a structured format that can be queried, updated & manipulated using SQL commands.
- A Table is composed of rows and columns, similar to a spreadsheet, each row represents a single record  or entry, and each column represents a specific attribute or characteristic of the records.

## Stored Procedure
- These are precompiled SQL statements/commands that are stored in the database.
- Stored Procedures are supported by major database management systems, such as, MySQL, PostgreSQL, Oracle etc.
- It offers serveral advantages: **Improved performance** (*faster execution*), **Centralized maintainance** (*can create, store & update stored procedures in one location*), & **Reuseability** (*facilitates code reuse and organization*).

## View
- This is like a virtual table created by combining data from multiple tables in a database.
- It doesn't hold any data itself, it only presents data from the underlying tables in a certan way, easier to query and analyze.

## Triggers
- This is a special type of stored procedure that automatically executes in response to certain events or actions occurring in a database.
- Triggers provides a way automate actions and enforce rules within your database.

## Normalization
- This is a process used to organize and clean up the data in a database effeciently (*by organizing the fields and tables of a database*).
- It aids to **Reduce clutter** (*remove duplicates*), **Organizing data logically** (*structure data into tables & define relationships between them*), **Avoiding mix-ups** (*avoid errors or incosistencies in data*), **Make data easy to find**.

## Denormalization
- This is the process of duplicating a database schema to allow for easier and quicker access.
- It aids to **Simplify access**, & **Adds Redundancy**. 

## Database warehousing
- This is the process of collecting, storing and managing large volumes of data from various data sources, to provide meaningful insight & support decision making with organizations/businesses.

## Application Programming Interfac(API)
- This is like a set of rules and tools that allows different software apps to communicate & interact with each other.
- APIs are crucial role in modern computing, enabling software applications to work together seamlessly and leverage each other's capabilities.