# Project Overview

This project focuses on designing and implementing a robust Hospital Database System to migrate existing Excel-based hospital records into a centralized relational database. The system improves data integrity, operational efficiency, security, and reporting by automating appointment management, enforcing business rules, and enabling department-wise revenue analysis.

# Project Objectives

Migrate hospital data from Excel to a structured relational database

Ensure data integrity, consistency, and uniqueness using proper constraints

Eliminate invalid, duplicate, and inconsistent records

Automate appointment scheduling rules and prevent conflicts

Implement role-based access control for sensitive patient data

Enable accurate department-wise monthly revenue reporting

# Project Description

The hospital previously relied on Excel files to manage patient records, doctor details, appointments, prescriptions, lab reports, and billing information. As data volume increased, this approach led to duplication, invalid entries, scheduling conflicts, and security risks.

This project involved designing a normalized relational database that captures all hospital operations while enforcing referential integrity and business rules. Existing Excel data was cleaned, validated, and migrated into the new system. The database also supports controlled access for doctors based on roles and generates automated revenue reports for management.

# Methods & Techniques Used

Relational Database Design & Normalization (3NF)

Primary Keys & Foreign Keys to ensure unique identification and relationships

Data Validation Rules & Constraints (CHECK, NOT NULL, ENUM)

Triggers & Stored Procedures to prevent invalid scheduling and past appointments

Role-Based Access Control (RBAC) for secure data access

SQL Queries & Views for reporting and analytics

ETL Process for data cleaning and Excel-to-database migration

# Key Outcomes

Eliminated duplicate and inconsistent patient, doctor, and appointment records

Enforced automated scheduling rules preventing double bookings

Improved data security with controlled access to sensitive patient information

Enabled accurate monthly revenue reports by department

Enhanced scalability, reliability, and operational efficiency of hospital data management
