# 📚 Online Book Store Management System

A **PostgreSQL-based database project** designed to manage the core operations of an online bookstore. The project focuses on relational database design, SQL queries, data management, and retrieving meaningful information from interconnected tables.

## 📌 About the Project

The Online Book Store Management System demonstrates how a bookstore can organize and manage its data using **PostgreSQL**. The database can be used to maintain information related to books, authors, customers, orders, and other essential bookstore operations.

This project was developed as a practical SQL and database management exercise, with a focus on writing queries, understanding table relationships, retrieving records efficiently, and performing different database operations.

## 🎯 Objectives

* Design and manage a relational database using PostgreSQL.
* Store and organize bookstore-related information.
* Practice SQL queries on structured datasets.
* Understand relationships between different database entities.
* Retrieve specific information using filtering and sorting.
* Perform data insertion, updating, deletion, and retrieval operations.
* Practice aggregate functions and grouping.
* Work with multiple tables using SQL joins.
* Improve understanding of real-world database management.

## 🛠️ Technologies Used

* **Database:** PostgreSQL
* **Language:** SQL
* **Database Tool:** PostgreSQL / pgAdmin
* **Version Control:** Git & GitHub

## 🗂️ Project Structure

```text
Online_Book_Store_Management/
│
├── online-book-store.sql
└── README.md
```

## 🧩 Database Concepts Covered

The SQL script demonstrates several important database concepts, including:

* Database and table creation
* Primary Keys
* Foreign Keys
* Constraints
* Data Types
* INSERT operations
* SELECT queries
* UPDATE operations
* DELETE operations
* WHERE conditions
* ORDER BY
* GROUP BY
* Aggregate Functions
* HAVING
* SQL Joins
* Subqueries
* Filtering and data analysis

## 🔍 SQL Operations

The project contains queries for working with bookstore data and performing operations such as:

```sql
SELECT
INSERT
UPDATE
DELETE
```

It also includes queries for filtering records, sorting results, grouping data, calculating aggregate values, and retrieving information from multiple related tables.

## 🔗 Relational Database Approach

The project follows a relational database approach where different types of bookstore information are stored in separate tables and connected through relationships.

For example:

```text
Authors
   │
   └──── Books
          │
          └──── Orders
                 │
                 └──── Customers
```

This approach helps reduce data duplication and makes the database easier to maintain and query.

## 🚀 How to Run the Project

### 1. Install PostgreSQL

Install PostgreSQL and optionally use **pgAdmin** to interact with the database.

### 2. Create a Database

Create a new PostgreSQL database for the project.

```sql
CREATE DATABASE online_book_store;
```

### 3. Open the SQL Script

Open:

```text
online-book-store.sql
```

in PostgreSQL/pgAdmin.

### 4. Execute the Queries

Run the SQL script to create the required database structure and execute the available queries.

## 📊 Learning Outcomes

Through this project, I practiced:

* Relational database concepts
* PostgreSQL syntax
* SQL query writing
* Database design
* Working with related tables
* Data manipulation
* Data retrieval and analysis
* Writing structured and reusable SQL queries

## 📁 Project File

The complete SQL script is available in:

**`online-book-store.sql`**

It contains the SQL work performed for this Online Book Store Management project.

## 👨‍💻 Author

**Yash Srivastava**

This project was created for learning and practicing **SQL, PostgreSQL, and relational database management concepts**.

