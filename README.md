# E-Governance-Citizen-Service-and-Complaint-Analytics-Platform

A comprehensive **Database Management System (DBMS)** project developed using **Oracle Database 10g Express Edition** for managing government citizen services and complaint handling efficiently. The system provides a centralized platform for citizen registration, service applications, complaint management, status tracking, and feedback collection while supporting analytical reporting for better governance.

---

##  Project Information

- **Project Title:** E-Governance Citizen Service and Complaint Analytics Platform
- **Course:** CSE-2424 – Database Management Systems
- **Semester:** Spring 2026
- **Database:** Oracle Database 10g Express Edition
- **Normalization:** Third Normal Form (3NF)

---

##  Project Overview

The E-Governance Citizen Service and Complaint Analytics Platform is designed to simplify interactions between citizens and government departments. Citizens can register, apply for government services, submit complaints, and provide feedback after resolution. Government officers can manage applications, update complaint statuses, and monitor departmental performance.

The project demonstrates practical implementation of relational database concepts including normalization, constraints, triggers, procedures, functions, views, and SQL queries.

---

##  Features

- Citizen Registration Management
- Government Department Management
- Officer Management
- Public Service Management
- Service Application Processing
- Complaint Registration
- Complaint Status Tracking
- Citizen Feedback Collection
- Analytical Reports
- Business Logic using Triggers
- Stored Procedures & Functions
- Database Views

---

##  Database Schema

The project consists of **8 normalized tables**:

- Citizens
- Departments
- Officers
- Services
- Applications
- Complaints
- Complaint_Status_History
- Feedback

All tables are connected using **Primary Keys** and **Foreign Keys** to maintain referential integrity.

---

##  Database Objects

### Tables
- 8 Tables

### Sequences
- Auto-generated IDs using Oracle Sequences

### Triggers
- Auto Increment Triggers
- Complaint Priority Trigger
- Auto Resolved Date Trigger
- Feedback Audit Trigger

### Views
- Analytics Summary
- Open Complaints
- Monthly Complaint Report
- Citizen Feedback Report

### Stored Procedures
- Submit Complaint
- Update Complaint Status
- Department Performance Report

### Functions
- Citizen Complaint Count
- Complaint Resolution Hours
- Complaint Status Label

---

##  SQL Queries Included

### Single Table Queries
- Citizen Registration Report
- Complaint Status Report
- Active Services
- Feedback Report
- Officer Report
- Pending Applications
- Average Resolution Time

### Join Queries
- Complaint Report
- Service Application Report
- Department Statistics
- Complaint History
- Citizen Satisfaction Report

### Subqueries
- Scalar Subqueries
- IN / NOT IN
- EXISTS
- Correlated Subqueries
- Derived Tables
- ALL Operator

### Advanced Queries
- Department Performance
- Monthly Complaint Report
- Overdue Complaints
- Complaint Timeline
- Average Resolution Time

---

##  Database Design

The database follows **Third Normal Form (3NF)**.

-  First Normal Form (1NF)
-  Second Normal Form (2NF)
-  Third Normal Form (3NF)

This minimizes redundancy and ensures data consistency.

---

##  Technologies Used

- Oracle Database 10g Express Edition
- SQL
- PL/SQL

---

##  Project Structure

```
├── SQL Script.sql
├── ER Diagram
├── Relational Schema
├── Project Report.pdf
└── README.md
```

---

##  How to Run

1. Install Oracle Database 10g Express Edition.
2. Open SQL Developer or SQL*Plus.
3. Execute the SQL script.
4. The script automatically:
   - Creates Sequences
   - Creates Tables
   - Creates Constraints
   - Creates Triggers
   - Inserts Sample Data
   - Creates Views
   - Creates Procedures
   - Creates Functions
   - Executes Sample Queries

---

##  Sample Dataset

The project includes realistic sample data based on government services in **Chittagong, Bangladesh**, including:

- 12 Citizens
- 10 Government Departments
- Officers
- Services
- Applications
- Complaints
- Complaint Status History
- Feedback

---

##  Learning Outcomes

This project demonstrates:

- Relational Database Design
- Entity Relationship Modeling
- Database Normalization
- Oracle SQL
- PL/SQL Programming
- Triggers
- Stored Procedures
- Functions
- Views
- Complex SQL Queries
- Database Integrity Constraints
