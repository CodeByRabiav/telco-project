# Telco Project - i2i Systems SQL Case Study

This repository contains my solutions for the i2i Systems Telco Project. The project involves database design, data migration from CSV files, and complex SQL analysis using Oracle XE.

##  Tech Stack & Environment
* **Database:** Oracle XE (Running on Docker)
* **Management Tool:** DBeaver
* **Language:** SQL

##  Project Structure
* `TABLE_CREATION_SCRIPTS.sql`: Contains DDL scripts for creating tables, primary keys, and relationships.
* `SOLUTIONS.sql`: Contains all SQL queries for the functional requirements, including technical explanations for each solution.

##  How to Run
1. **Database Setup:** Start your Oracle XE instance via Docker.
2. **Schema Creation:** Run the scripts in `TABLE_CREATION_SCRIPTS.sql` to build the database structure.
3. **Data Import:** Import the provided `.csv` files into their respective tables (`CUSTOMERS`, `TARIFFS`, `MONTHLY_STATS`) using DBeaver's import wizard.
4. **Analysis:** Execute the queries in `SOLUTIONS.sql` to see the analytical results.

##  Functional Requirements Addressed
The project covers the following analytical scenarios:
1. **Tariff-Based Queries:** Filtering and finding specific subscribers.
2. **Tariff Distribution:** Statistical breakdown of tariff popularity.
3. **Signup Analysis:** Tracking the earliest customers and their geographical distribution.
4. **Data Integrity:** Identifying missing monthly records.
5. **Usage Analysis:** Highlighting customers nearing or exceeding their package limits.
6. **Payment Status:** Analyzing debt and payment distributions across tariffs.

---
**Note:** Each SQL solution in `SOLUTIONS.sql` includes a detailed 3-sentence technical explanation as per the project requirements.
