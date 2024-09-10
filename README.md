# SQL
Beginner Level:
Introduction to SQL

What is SQL? Importance of databases
Types of databases: Relational vs. Non-relational databases
SQL vs NoSQL
SQL Basics

Data Definition Language (DDL): CREATE, ALTER, DROP
Data Manipulation Language (DML): SELECT, INSERT, UPDATE, DELETE
Data Query Language (DQL): Basic SELECT queries
Data Control Language (DCL): GRANT, REVOKE
Transaction Control Language (TCL): COMMIT, ROLLBACK, SAVEPOINT
Basic SQL Queries

Selecting columns from tables (SELECT)
Using WHERE clause for filtering
Sorting results using ORDER BY
Limiting results with LIMIT
Basic arithmetic and string operations
DISTINCT keyword to eliminate duplicates
Filtering and Conditional Queries

Using WHERE, AND, OR, NOT
Logical operators: BETWEEN, IN, LIKE, IS NULL
Pattern matching with LIKE (e.g., % and _)
Sorting Data

Sorting using ORDER BY
Sorting in ascending (ASC) and descending (DESC) order
Basic Joins

Understanding relations between tables
INNER JOIN: Retrieving data from multiple tables
LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN
Intermediate Level:
Advanced Filtering

Using HAVING for filtering with aggregate functions
Aliases with AS to rename columns/tables
Functions and Aggregation

Aggregate functions: COUNT(), SUM(), AVG(), MIN(), MAX()
String functions: CONCAT(), SUBSTRING(), UPPER(), LOWER(), etc.
Date functions: NOW(), DATE(), DATEDIFF(), DATE_FORMAT()
Numeric functions: ROUND(), FLOOR(), CEIL()
Joins and Subqueries

INNER, OUTER, CROSS, SELF joins
Subqueries (nested queries)
EXISTS, IN, ANY, ALL with subqueries
Grouping Data

Grouping with GROUP BY
Using aggregate functions with GROUP BY
Difference between WHERE and HAVING
Set Operations

UNION, UNION ALL
INTERSECT, EXCEPT
Indexes

Introduction to indexes
Creating and using indexes (CREATE INDEX)
Impact of indexes on performance
UNIQUE index
Constraints

Primary Key (PRIMARY KEY)
Foreign Key (FOREIGN KEY)
Unique constraints (UNIQUE)
Check constraints (CHECK)
Default value constraints (DEFAULT)
Advanced Level:
Advanced Subqueries

Correlated subqueries
Scalar subqueries, row subqueries
Common Table Expressions (CTEs) with WITH clause
Views

Creating and managing views (CREATE VIEW, DROP VIEW)
Using views for simplified querying
Updating views
Transactions

ACID properties (Atomicity, Consistency, Isolation, Durability)
Implementing transactions using BEGIN, COMMIT, ROLLBACK
Savepoints in transactions (SAVEPOINT)
Triggers

Understanding triggers
Creating and managing triggers (CREATE TRIGGER)
Use cases: Before insert, after update, etc.
Stored Procedures & Functions

Creating and calling stored procedures (CREATE PROCEDURE)
Creating and using functions (CREATE FUNCTION)
Differences between stored procedures and functions
Parameters: IN, OUT, INOUT
Advanced Joins

Recursive joins
Complex join conditions (joining on multiple columns)
Database Optimization

Query optimization techniques
Using EXPLAIN to analyze query performance
Indexing strategies for performance
Partitioning large tables
User Management and Security

Creating users and managing permissions (CREATE USER, GRANT, REVOKE)
Database roles
Password policies and encryption
Normalization and Denormalization

Understanding the different Normal Forms (1NF, 2NF, 3NF, BCNF)
Practical examples of normalization and denormalization
Advanced SQL Tools and Techniques

Window functions: ROW_NUMBER(), RANK(), DENSE_RANK(), LEAD(), LAG()
Pivot tables
Handling time zones with SQL
JSON data handling in SQL
Full-text search
Advanced error handling
