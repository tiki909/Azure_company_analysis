# Azure_company_analysis

Certainly! Here's a README summary for the activities you performed, explaining that you created a database from collected data using MySQL with the assistance of this conversation:

---

# MySQL Database Creation Summary

## Overview

This repository documents the process of creating a MySQL database named `azure_company` with various tables and relationships. The database was designed to store information about employees, departments, projects, and their relationships.

## Steps

### 1. Database and Table Creation

- **Schema Creation:**
  - A new schema named `azure_company` was created to house the tables.

- **Tables:**
  - Tables `employee`, `departament`, `dept_locations`, `project`, and `works_on` were defined to store employee information, department details, department locations, project details, and work assignments, respectively.

### 2. Data Insertion

- **Employee Data:**
  - Employee data was inserted into the `employee` table.

- **Department Data:**
  - Department data was inserted into the `departament` table.

- **Project Data:**
  - Project data was inserted into the `project` table.

- **Works On Data:**
  - Work assignment data was inserted into the `works_on` table.

- **Department Locations Data:**
  - Department locations data was inserted into the `dept_locations` table.

### 3. Foreign Key Relationships

- **Employee-Department Relationship:**
  - A foreign key relationship was established between the `employee` and `departament` tables, linking employees to their respective departments.

- **Works On Relationship:**
  - A foreign key relationship was created between the `works_on` table and the `employee` and `project` tables, indicating work assignments.

### 4. Additional Details

- **Constraints:**
  - Various constraints were added to ensure data integrity, such as primary keys, foreign keys, and check constraints.

- **Default Values:**
  - Default values were set for certain columns.

## Conclusion

This repository serves as a comprehensive guide to creating a MySQL database and populating it with relevant data. The database structure facilitates the management of employee, department, project, and work assignment details. Feel free to explore the SQL scripts and data files for further details.

---
