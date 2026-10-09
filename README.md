# Database Management Systems (DBMS) Laboratory

This repository contains SQL source code, relational schemas, advanced queries, execution plans, and animated execution outputs for **DBMS Laboratory Experiments (3 to 8)**.

---

## 📑 Table of Contents

| Experiment | Title / Description | Link |
| :---: | :--- | :---: |
| **03** | **SQL Queries, Aggregates & Grouping**<br>Demonstrates Selection, Projection, Aggregates, `GROUP BY`, `HAVING`, `CASE` expressions, and `ORDER BY` across an Employee–Department–Project schema. | [View Experiment 3](./EXPERIMENT-3/README.md) |
| **04** | **Advanced Joins, Subqueries & Execution Plans**<br>Demonstrates `INNER JOIN`, `LEFT JOIN`, `self-join`, `3-way join`, correlated subqueries, `EXISTS`, simulated `INTERSECT`/`EXCEPT`, and `EXPLAIN` query analysis. | [View Experiment 4](./EXPERIMENT-4/README.md) |
| **05** | **SQL Views & Recursive CTE**<br>Implements Department Salary Summary views, Employee Hierarchy views, view updatability testing, and recursive CTE for organizational reporting chains. | [View Experiment 5](./EXPERIMENT-5/README.md) |
| **06** | **Stored Procedures & Triggers**<br>Implements `transfer_employee` stored procedure with custom error handling (`SIGNAL SQLSTATE`), `BEFORE UPDATE` salary validation trigger, and `AFTER UPDATE` audit logging trigger. | [View Experiment 6](./EXPERIMENT-6/README.md) |
| **07** | **Database Normalization (UNF to BCNF)**<br>Decomposes a denormalized sales table from UNF through 1NF, 2NF, 3NF, and BCNF, with verification of lossless join decomposition and dependency preservation. | [View Experiment 7](./EXPERIMENT-7/README.md) |
| **08** | **Transaction Control (TCL) & Isolation Levels**<br>Demonstrates banking transactions using `BEGIN`, `COMMIT`, `ROLLBACK`, `SAVEPOINT`, partial failures, and session isolation levels (`READ COMMITTED`, `REPEATABLE READ`, `SERIALIZABLE`). | [View Experiment 8](./EXPERIMENT-8/README.md) |

---

## 🛠️ Technologies & Platforms
- **Database Engine**: MySQL 8.0+
- **Lab Environment**: byteXL / MySQL Workbench / Command Line Client

---

## 📂 Repository Structure
```text
DBMS-LAB/
├── EXPERIMENT-3/
│   ├── README.md
│   └── output.gif
├── EXPERIMENT-4/
│   ├── README.md
│   └── output.gif
├── EXPERIMENT-5/
│   ├── README.md
│   └── output.gif
├── EXPERIMENT-6/
│   ├── README.md
│   └── output.gif
├── EXPERIMENT-7/
│   ├── README.md
│   └── output.gif
├── EXPERIMENT-8/
│   ├── README.md
│   └── output.gif
└── README.md
```