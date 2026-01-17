# Project Overview

The Hospital Database Creation and Data Migration project focuses on transforming an Excel-based hospital record system into a structured, secure, and scalable relational database system.
The hospital currently manages patient records, doctor information, appointments, lab reports, prescriptions, and billing using spreadsheets, which leads to data duplication, errors, weak security, and reporting limitations.

This project designs and implements a centralized hospital database that ensures data accuracy, enforces business rules, controls access, and supports analytical reporting such as department-wise revenue tracking.

# Project Objectives

The main objectives of the project are:

1) Ensure Data Uniqueness:
Create unique identifiers for patients, doctors, departments, and appointments.

2) Maintain Data Integrity:
Enforce relationships between patients, doctors, departments, and appointments using foreign keys.

3) Eliminate Invalid Data:
Restrict gender, appointment status, and date values to predefined valid formats.

4) Prevent Scheduling Conflicts:
Avoid double-booking doctors and prevent appointments from being scheduled in the past.

5) Implement Role-Based Access Control:
Ensure that only authorized doctors can view patient data based on their role and department.

6) Enable Business Reporting:
Generate monthly revenue and departmental performance reports.

# Dataset Description

The original dataset comes from Excel files used by the hospital. It includes the following information:

Data Type	Description
Patients	Patient name, age, gender, contact details
Doctors	Doctor name, specialization, department
Departments	Department ID, department name
Appointments	Patient, doctor, date, time, status
Prescriptions	Medicines prescribed by doctors
Lab Reports	Test results linked to patients
Billing	Charges for consultations, tests, and medicines

These Excel records had:

1) Duplicate entries

2) Missing IDs

3) Invalid values (e.g., gender = "X", status = "On Hold")

4) No linking between tables

5) All this data is cleaned and migrated into structured relational tables.

# Methods and Techniques Used
a) Database Design:

Entity-Relationship (ER) modeling

Normalization to remove redundancy

Primary and Foreign key implementation

b) Data Validation:

CHECK constraints for:

Gender: ('M','F','O')

Status: ('Scheduled','Completed','Cancelled')

Date validation to prevent past appointments

c) Referential Integrity:

Foreign keys to link:

Appointments → Patients

Appointments → Doctors

Doctors → Departments

d) Automation Using SQL:

Triggers to:

Prevent double-booking of doctors

Block appointments in the past

Stored procedures for inserting and validating data

e) Role-Based Security:

User roles:

Senior Doctor

Doctor

Views and permissions used to restrict access

f) Reporting:

SQL queries and views to generate:

Monthly revenue by department

Patient and appointment summaries

# Key Outcomes

The project delivers the following outcomes:

A fully structured relational hospital database

Elimination of duplicate and invalid data

Enforced data accuracy and consistency

Automated prevention of scheduling conflicts

Secure access based on doctor role and department

Department-wise monthly revenue reports

Improved hospital efficiency and decision-making
