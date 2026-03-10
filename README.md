# MySQL Revision & Practice Lab 🐬

A comprehensive repository dedicated to practicing and revising fundamental and advanced concepts in MySQL. This collection of SQL scripts serves as a quick reference guide and hands-on laboratory for database design, querying, and optimization.

## 🚀 Key Concepts Covered

The repository is structured around various core database operations:

### 1. Database Creation & Schema Design
- **E-Commerce Database (`ecom.sql`)**: Designing tables for `customers`, `products`, and `orders`. Setting up Primary Keys, Foreign Keys, and inserting dummy data.
- **Healthcare Database (`healthcare.sql`)**: Designing interconnected tables for `patients`, `doctors`, and `appointments`. 
- **Basic Intro (`Intro.sql`)**: Fundamentals such as `CREATE TABLE`, `INSERT`, `UPDATE`, `DELETE`, and constraints like `UNIQUE` and `CHECK`.

### 2. Querying & Data Aggregation
Both the e-commerce and healthcare databases contain script sections dedicated to:
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- Aggregate functions (`COUNT`, `SUM`, `AVG`)
- Table Joins (`joins.sql` and queries inside `ecom.sql`/`healthcare.sql`)

### 3. Advanced Database Features
- **Stored Procedures (`Stored Prodcure.sql`)**: Examples of parameterized execution blocks.
- **Views (`view.sql`)**: Storing pre-defined, complex queries as virtual tables.
- **Triggers (`trigger.sql`)**: Automatically executing rules upon insertions or updates.
- **Cursors (`cursore.sql`)**: Row-by-row processing within stored routines.
- **Transaction Control Language / TCL (`TCL.sql`)**: Utilizing `COMMIT` and `ROLLBACK` for transaction safety.

### 4. Built-in Functions
- String manipulating tools (`CONCAT`)
- Date/Time functions (`DATE_FORMAT`, `TIME_FORMAT`, `TIMESTAMPDIFF`, `DATEDIFF`) covered in `function date time 2.sql`, `function, date tine.sql`, and `function.sql`.

## 🛠️ How to Use

1. **Locally via MySQL Workbench / CLI**:
   - Create an empty database: `CREATE DATABASE my_practice;`
   - Source the scripts: `SOURCE path/to/ecom.sql;`
2. **Reviewing Code**: Open the `.sql` files directly on GitHub to refresh syntax for specific operations.

---
*Keep querying!*