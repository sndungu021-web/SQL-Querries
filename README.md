# SQL Data Exploration & Analysis

##  Project Overview
This repository contains a series of SQL scripts designed to analyze the sales performance of a given shop outlet. The project focuses on transforming raw relational data into a structured format ready for business reporting.

## Database Schema
* **Source Data:** PostgreSQL
* **Dataset:** Sales Invetory
* **Key Tables:** `Orders`, `Customers`, `Products`, and `orders`.

## SQL Techniques Applied
* **Complex Joins:** Utilizing Multi-level Inner/Left Joins to consolidate disparate tables.
* **Window Functions:** Implementing `RANK()` for trend analysis.
* **CTEs (Common Table Expressions):** Using `WITH` clauses to break down complex logic into readable steps.
* **Data Cleaning:** Handling `NULL` values, standardizing date formats, and removing duplicates using `DISTINCT` and `ROW_NUMBER()`.
* **Aggregations:** Advanced grouping for KPI calculation.

## Business Questions Answered
1. Which product categories drive the highest profit margins?
2. What is the average customer retention rate month-over-month?

## How to Run the Scripts
1. Import the schema found in `/schema.sql`.
2. Load the raw data from `/data/`.
3. Execute the analysis scripts in the `/queries/` folder.
