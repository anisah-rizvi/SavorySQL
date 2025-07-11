# SavorySQL
SavorySQL is a beginner-friendly MySQL project simulating a restaurant system with tables like Customers, Bookings, and MenuItems. It covers key SQL concepts such as joins, views, stored procedures, subqueries, and table alterations—perfect for learners to practice and strengthen their database skills.
Sure! Here's a complete `README.md` file for your **SavorySQL** project, written in a clean and beginner-friendly style:

---

````markdown
# 🍽️ SavorySQL – Restaurant Database Project

SavorySQL is a beginner-friendly MySQL project simulating a restaurant management system. It helps you practice core SQL concepts like table creation, relationships, views, stored procedures, joins, subqueries, and more – all through a simple yet realistic restaurant scenario.

---

## 📂 Project Structure

- `savorysql_schema.sql` – Creates database schema (Customers, Bookings, MenuItems, Staff, Orders)
- `savorysql_data.sql` – Inserts sample data into each table
- `savorysql_queries.sql` – Practice queries (JOINs, GROUP BY, views, procedures, etc.)

---

## 🛠️ Features Practiced

- ✅ Table creation with constraints
- ✅ Relationships: One-to-Many, Many-to-Many
- ✅ INNER JOIN, LEFT JOIN
- ✅ GROUP BY, HAVING, ORDER BY
- ✅ Subqueries and string functions
- ✅ Views and Stored Procedures
- ✅ ALTER TABLE operations

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/SavorySQL.git
cd SavorySQL
````

### 2. Open MySQL CLI or MySQL Workbench

### 3. Import the Schema and Data

```sql
SOURCE savorysql_schema.sql;
SOURCE savorysql_data.sql;
```

### 4. Run Practice Queries

```sql
SOURCE savorysql_queries.sql;
```

---

## 📌 Example Tables

* `Customers`: Stores customer details
* `MenuItems`: Items available for order
* `Bookings`: Table reservations
* `Orders`: Customer orders linked to menu
* `Staff`: Employee info

---

## 🎓 Ideal For

* Beginners learning MySQL
* Students working on SQL mini-projects
* Anyone wanting hands-on practice with relational databases

---

## 📬 Feedback

Feel free to fork, contribute, or suggest improvements!
Created with ❤️ for learners.

```
