# Practice

## Analytical Solution Architecture

Analytical Solution Architecture made in draw.io

![Analytical Solution Architecture](https://github.com/brabus000/DE-101/blob/main/Module%2001/images/Analytical_Solution_Architecture.drawio.png)

In this example, the analytical system is divided into three layers of architecture:

**Source layer:** Business systems where data is generated (order databases, CRM, Google Analytics, warehouse systems). These systems are called OLTP - they work fast and are designed for transactions, but not for analytics. 

**Storage layer:** The central Data Warehouse, where data is transferred using the ETL/ELT process (Extract, Transform/Load, Load/Transform). There are usually at least two layers inside the repository: Staging (a copy of data from sources) and Data Model (processed data for business).

**Business Layer:** Interfaces through which users (marketers, financiers) access data. These are BI tools (Tableau, Power BI, Excel) and SQL queries.

## Excel Dashboard
