# Project Overview

The Python-Driven UI for Advanced SQL Database Operations project focuses on building a user-friendly web application that allows non-technical users to interact with a MySQL database without writing SQL queries.

Using Python (Streamlit) as the frontend and MySQL as the backend, the application enables users such as managers, team leads, and operations staff to view data, update records, run stored procedures, and generate reports through simple buttons and forms.
This project demonstrates how real-world business applications bridge the gap between databases and end users through an intuitive interface.

# Project Objectives

The key objectives of this project are:

Eliminate Direct SQL Dependency

Allow users to interact with databases without knowing SQL syntax.

Develop a Robust Database Backend

Implement tables, views, stored procedures, and functions for business logic.

Build an Interactive Web Interface

Create a Streamlit-based UI for real-time database interaction.

Enable Business Operations

Support tasks like inventory updates, order processing, and report generation.

Ensure Data Accuracy and Consistency

Centralize business rules within the database using procedures and functions.

Simulate Real-World Enterprise Applications

Demonstrate how backend and frontend systems work together in production environments.

# Dataset Description

The dataset represents a business inventory and order management system, stored in a MySQL database. It includes:

Dataset Component	Description
Products	Product ID, name, price, category
Inventory	Stock levels, restock thresholds
Orders	Order details, order date, status
Shipments	Shipment tracking and delivery status
Sales Records	Product-wise and date-wise sales

The data is structured across multiple relational tables and accessed dynamically through views, stored procedures, and SQL functions.

# Methods and Techniques Used
a) Database Design (MySQL)

Relational schema design

Primary and foreign key constraints

Normalization to reduce redundancy

b) Advanced SQL Features

Views

For summaries like product history and sales reports

Stored Procedures

For actions such as:

Receiving orders

Updating inventory

Marking orders as completed

Functions

For calculations like:

Checking low-stock products

Business rule validations

c) Python–MySQL Integration

MySQL Connector / SQLAlchemy for database connectivity

Secure execution of queries from Python

d) Streamlit Frontend Development

Interactive UI elements:

Buttons

Dropdowns

Forms

Real-time data display using tables and charts

Event-driven execution of SQL logic

e) Layered Architecture

Database layer → Business logic

Python layer → Data processing

UI layer → User interaction

# Key Outcomes

A fully functional Python-MySQL web application

Non-technical users can operate database actions easily

Advanced SQL logic abstracted behind UI controls

Real-time data updates and reporting

Improved usability, efficiency, and error reduction

Practical demonstration of full-stack data application development
