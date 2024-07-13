# Customer Segmentation and Sales Analysis in a Bike Store

## Project Overview

This project aims to leverage SQL to perform an in-depth analysis of a bike store's sales data. The focus is on customer segmentation, sales trends, product performance, and store performance. The analysis provides actionable insights to enhance sales strategies and improve customer loyalty.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Cleaning](#data-cleaning)
3. [Database Creation](#database-creation)
4. [Importing Dataset](#importing-dataset)
5. [Business Questions](#business-questions)
6. [Insights](#insights)
7. [Conclusion](#conclusion)
8. [Files in the Repository](#files-in-the-repository)
9. [How to Run](#how-to-run)
10. [License](#license)
11. [Contact](#contact)

## Introduction

### Project Overview
This project analyzes sales data from a bike store to identify key trends and insights. The analysis includes customer segmentation, sales trends, product performance, and store performance.

### Objectives
- Segment customers based on their purchase behavior.
- Analyze sales trends over time.
- Identify top-performing products and brands.
- Evaluate store performance.

## Data Cleaning

### Data Preparation
Data was prepared by extracting relevant tables and fields from the provided dataset.

### Handling Missing Values
Missing values were handled through imputation and data exclusion where appropriate.

### Data Transformation
Data was transformed to ensure consistency and usability for analysis.

## Database Creation

### Creating the Bike Store Database
The `bike_store` database was created using SQL commands to structure the data.

### Table Structure and Relationships
The database includes tables for customers, orders, order items, products, brands, and stores, with appropriate relationships established between them.

## Importing Dataset

### Loading Data into Tables
Data was loaded into the respective tables using SQL import commands.

### Verifying Data Integrity
Steps were taken to verify the accuracy and integrity of the imported data.

## Business Questions

### Key Business Questions
- Which customers have spent more than the average customer spend?
- What are the top 5 most popular bike brands by quantity sold in a specific time period?
- Find all customers who have placed more than a certain number of orders.
- What is the average order value for customers who have placed more than 5 orders?
- Identify customers who have placed orders in every month of the current year.

### SQL Queries for Analysis
The analysis was conducted using various SQL queries involving subqueries and Common Table Expressions (CTEs).

## Insights

### Customer Segmentation
Customers were segmented into Platinum, Gold, and Silver categories based on their purchase quantities.

### Sales Trends and Patterns
Monthly sales trends were analyzed to identify high-level patterns.

### Product and Brand Performance
Top-selling products and brands were identified and analyzed.

### Store Performance
Store performance was evaluated based on sales metrics.

## Conclusion

### Summary of Findings
Key insights derived from the analysis were summarized.

### Recommendations
Recommendations were provided based on the findings to help improve sales and customer engagement.

## Files in the Repository

- `README.md`: This README file.
- `data_model.png`: Image of the database schema.
- `create_database.sql`: SQL script for creating the bike store database.
- `import_data.sql`: SQL script for importing data into the database.
- `queries.sql`: SQL queries used for analysis.
- `presentation.pptx`: PowerPoint presentation summarizing the project.

## How to Run

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/bike-store-analysis.git
   cd bike-store-analysis

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or inquiries, please contact [Ritik Sunil Khapre](mailto:ritik.khapre5202.com).

