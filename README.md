# Global Superstore Management Database Project

## Overview

This project is focused on developing a relational database for a global superstore that sells a wide range of products. The objective is to create an efficient data management system that handles customer accounts, orders, payment processing, refunds, product returns, and employee management. The database also supports analytical queries to analyze store performance, top customers, and other business insights.

## Features

- **Customer Management**: Track customer registration details, orders, and payment statuses.
- **Order Fulfillment**: Support for delivery, pickup, and in-store orders, with payment processing.
- **Product Returns & Refunds**: Manage return processes and refunds through online and physical stores.
- **Employee Management**: Maintain records of employees across multiple stores.
- **Business Insights**: Queries and reports on store performance, high-value customers, and payment methods.

## Project Structure

### 1. **Entity-Relationship Model**
   - An Entity-Relationship diagram (ERD) was created to model the data relationships between customers, orders, stores, employees, and payment systems.
   - The database includes tables for stores, customers, orders, payments, deliveries, refunds, and employees.

### 2. **UML Diagram**
   - A UML diagram was used to visualize the flow of processes within the system and the interactions between different modules.

### 3. **SQL Queries**
   - A set of SQL queries was implemented to analyze the data and generate business insights. These queries are used for operations like finding the store with the highest revenue, identifying top customers, and analyzing payment modes.
   
   Some example SQL queries:
   - Find all delivery orders.
   - Find customers who made purchases using a credit card.
   - Calculate the total amount spent by each customer.
   - Identify the store with the highest revenue.

### 4. **NoSQL Implementation**
   - MongoDB is used to demonstrate aggregation queries, such as finding sales revenue by payment mode and identifying employees in the accounts department.

### 5. **Python Integration**
   - Python is used to connect to the MySQL database and generate visualizations such as:
     - Distribution of revenue by payment method (Donut Chart).
     - Total amount spent by each customer (Bar Chart).
     - Top 10 high-value customers and their average order value (Bar Chart).

## How to Use

1. **Set up MySQL Database**:
   - Install MySQL and create a new database.
   - Use the SQL schema and queries provided to set up the tables and populate them with sample data.

2. **Set up MongoDB (Optional)**:
   - If you want to explore NoSQL functionality, set up a MongoDB instance and import the relevant data.
   
3. **Install Dependencies**:
   - Make sure you have the following Python libraries installed:
     - `mysql-connector-python` (for MySQL connection)
     - `matplotlib` and `seaborn` (for visualizations)
     - `pymongo` (for MongoDB integration)

4. **Run Python Scripts**:
   - Use the Python scripts to run data queries and visualize the results using bar charts and donut charts.


## Technologies Used
  - Database: MySQL, MongoDB (NoSQL)
  - Backend: Python
  - Data Visualization: Matplotlib, Seaborn
  - Database Management: MySQL Workbench, MongoDB Compass

## Conclusion
This project provides a comprehensive approach to building a relational and NoSQL database for managing operations of a global superstore. By leveraging SQL, NoSQL, and Python, the system allows for efficient data management and actionable business insights, enabling the store to optimize its operations and customer service.
