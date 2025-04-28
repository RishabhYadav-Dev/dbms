# dbms

© 2024 MUSA. All rights reserved. This material is the exclusive property of MUSA. Unauthorized reproduction, distribution, or use
is strictly prohibited.
MUMBAI UNIVERSITY STUDENTS ASSOCIATION (MUSA)
VIVA QUESTION AND ANSWER OF DBMS
 S.E SEM-IV BRANCH: COMPS FOR SUMMER SESSION 2025
VIVA QUESTION AND ANSWER
Module 1: Introduction to Database Concepts
Q.1) What is a database?
Ans: A database is a collection of logically related data, organized in a structured way so that it can
be easily accessed, managed, and updated.
Q.2) What are the characteristics of a database?
Ans: Characteristics include data integrity, security, non-redundancy, concurrency control, data
independence, and data sharing.
Q.3) How is a DBMS different from a traditional file system?
Ans: DBMS provides better data consistency, less redundancy, centralized control, security, and
backup facilities, unlike file systems.
Q.4) What is data abstraction?
Ans: Data abstraction refers to hiding the complex details of the database and showing only
essential features to the users. It has three levels: physical, logical, and view.
Q.5) What is data independence?
Ans: Data independence is the capacity to change the schema at one level without having to
change the schema at the next higher level.
Q.6) Explain the architecture of a DBMS.
Ans: It consists of three levels: External (view), Conceptual (logical), and Internal (physical) level.
Q.7) Who is a database administrator (DBA)?
Ans: A DBA is a person responsible for managing and maintaining the database system including
performance tuning, access control, backup, and recovery.
Q.8) What is metadata?
Ans: Metadata is data that describes other data, such as table names, column names, data types,
and constraints.
Q.9) List advantages of using DBMS.
Ans: Reduced data redundancy, improved data security, easy data access, data consistency, and
backup and recovery.
Q.10) Define DBMS with example.
Ans: DBMS stands for Database Management System. It is software for storing and managing data.
Example: MySQL, Oracle, PostgreSQL.
Module 2: Entity–Relationship Data Model
© 2024 MUSA. All rights reserved. This material is the exclusive property of MUSA. Unauthorized reproduction, distribution, or use
is strictly prohibited.
Q.1) What is an entity?
Ans: An entity is a real-world object or concept that can have data stored about it in a database.
Q.2) What is the difference between strong and weak entity sets?
Ans: A strong entity set has a primary key, whereas a weak entity set does not and depends on a
strong entity for identification.
Q.3) What are attributes in ER model?
Ans: Attributes describe the properties of an entity. They can be simple, composite, derived, singlevalued, or multi-valued.
Q.4) What is a primary key?
Ans: A primary key is a unique identifier for an entity in a table and cannot be null.
Q.5) What is cardinality in ER model?
Ans: Cardinality defines the number of entities to which another entity can be associated via a
relationship.
Q.6) What is participation constraint?
Ans: It indicates whether all or only some entity instances participate in a relationship. It can be
total or partial.
Q.7) Define generalization.
Ans: Generalization is the process of extracting shared characteristics from two or more classes and
combining them into a generalized superclass.
Q.8) What is specialization in ER model?
Ans: Specialization is the process of creating new sub-entities from an existing entity based on
some distinguishing characteristics.
Q.9) What is aggregation in ER diagram?
Ans: Aggregation is a higher-level abstraction where relationships are treated as higher-level
entities.
Q.10) What is an EER diagram?
Ans: Extended ER diagram includes concepts like generalization, specialization, and aggregation to
represent more complex relationships.
Module 3: Relational Model and Relational Algebra
Q.1) What is the relational model?
Ans: It is a model based on first-order predicate logic where data is organized into relations
(tables).
Q.2) Define relation and relational schema.
Ans: A relation is a table with rows and columns. A relational schema is the blueprint of a table,
including column names and data types.
Q.3) What is a candidate key?
Ans: A candidate key is a set of attributes that uniquely identifies a tuple in a relation. One of them
becomes the primary key.
Q.4) What is relational algebra?
Ans: Relational algebra is a procedural query language that operates on relations and uses
operators to perform queries.
© 2024 MUSA. All rights reserved. This material is the exclusive property of MUSA. Unauthorized reproduction, distribution, or use
is strictly prohibited.
Q.5) Explain selection and projection in relational algebra.
Ans: Selection (σ) chooses rows that satisfy a condition; projection (π) selects specific columns.
Q.6) What is Cartesian product?
Ans: It combines all tuples of one relation with all tuples of another, producing all possible
combinations.
Q.7) What is join operation in relational algebra?
Ans: A join combines related tuples from two relations into single tuples based on a common
attribute.
Q.8) Explain the rename operation.
Ans: Rename (ρ) changes the name of the output relation or its attributes.
Q.9) How is ER model mapped to a relational model?
Ans: Entities become tables, attributes become columns, and relationships are represented using
foreign keys.
Q.10) What is the use of set operators in relational algebra?
Ans: Set operators like union, intersection, and difference combine or compare tuples from two
relations.
Module 4: Structured Query Language (SQL)
Q.1) What is SQL?
Ans: SQL stands for Structured Query Language. It is used for storing, manipulating, and retrieving
data in databases.
Q.2) What is DDL in SQL?
Ans: DDL (Data Definition Language) includes commands like CREATE, ALTER, DROP to define
database schema.
Q.3) What is DML in SQL?
Ans: DML (Data Manipulation Language) includes commands like SELECT, INSERT, UPDATE, DELETE
to manipulate data.
Q.4) What are integrity constraints?
Ans: Rules that ensure accuracy and consistency of data like primary key, foreign key, unique, not
null, and check constraints.
Q.5) What are aggregate functions in SQL?
Ans: Functions like COUNT, SUM, AVG, MAX, MIN used to perform calculations on data sets.
Q.6) What is GROUP BY clause?
Ans: GROUP BY is used to group rows that have the same values into summary rows.
Q.7) What is a VIEW in SQL?
Ans: A view is a virtual table created by a query. It does not store data physically.
Q.8) Explain JOIN with an example.
Ans: JOIN combines rows from two or more tables based on a related column. Example: SELECT *
FROM A JOIN B ON A.id = B.id.
Q.9) What is a nested query?
Ans: A query within another SQL query is called a nested or sub-query.
© 2024 MUSA. All rights reserved. This material is the exclusive property of MUSA. Unauthorized reproduction, distribution, or use
is strictly prohibited.
Q.10) What are triggers in SQL?
Ans: Triggers are procedural code automatically executed in response to events like INSERT,
UPDATE, or DELETE on a table.
Module 5: Relational Database Design
Q.1) What is normalization?
Ans: Normalization is the process of organizing data to reduce redundancy and improve data
integrity.
Q.2) What is a functional dependency?
Ans: A functional dependency exists when one attribute uniquely determines another attribute.
Q.3) What are the problems in unnormalized data?
Ans: Redundancy, insertion anomalies, deletion anomalies, and update anomalies.
Q.4) Explain 1NF with example.
Ans: A relation is in 1NF if it contains only atomic values and no repeating groups. Example:
splitting multiple phone numbers into different rows.
Q.5) What is 2NF?
Ans: A relation is in 2NF if it is in 1NF and all non-key attributes are fully functionally dependent on
the primary key.
Q.6) What is 3NF?
Ans: A relation is in 3NF if it is in 2NF and has no transitive dependency.
Q.7) What is BCNF?
Ans: Boyce-Codd Normal Form is a stricter version of 3NF where every determinant is a candidate
key.
Q.8) What is a candidate key?
Ans: An attribute or set of attributes that can uniquely identify a record in a table.
Q.9) What is a primary key?
Ans: A unique identifier for a tuple in a table chosen from candidate keys.
Q.10) What are anomalies in DB design?
Ans: Insertion, deletion, and update anomalies caused by poor database design.
Module 6: Transactions, Concurrency, and Recovery
Q.1) What is a transaction?
Ans: A transaction is a sequence of operations performed as a single logical unit of work.
Q.2) What are ACID properties?
Ans: Atomicity, Consistency, Isolation, Durability — ensure reliable processing of transactions.
Q.3) What are the states of a transaction?
Ans: Active, partially committed, committed, failed, and aborted.
Q.4) What is concurrency control?
Ans: It manages simultaneous operations without conflicting, ensuring database consistency.
Q.5) What is serializability?
Ans: It is the highest level of isolation where transactions appear to execute in a serial order.
Q.6) What is a lock-based protocol?
Ans: It uses locks to control concurrent access to data items.
Q.7) What is a timestamp-based protocol?
Ans: Each transaction is given a timestamp, and conflicts are resolved using these timestamps.
Q.8) What is log-based recovery?
Ans: In log-based recovery, all transactions are recorded in a log before execution. It helps recover
after a crash.
Q.9) What is a deadlock?
Ans: A deadlock is a situation where two or more transactions are waiting for each other to release
resources.
Q.10) How can deadlocks be handled in DBMS?
Ans: Deadlocks can be prevented, avoided, detected, or resolved using timeout, wait-die, woundwait, or deadlock detection algorithms.
***** ALL THE BEST*****
