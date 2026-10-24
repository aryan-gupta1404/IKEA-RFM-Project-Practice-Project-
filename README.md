# IKEA-RFM-Project-Practice-Project-
Tools & Technologies: MySQL Workbench · Python · Pandas · Power BI · DAX

## Project Overview

This project explores customer purchasing behaviour, customer segmentation, and potential churn through an IKEA Gifting customer analytics business case.

The analysis uses the Online Retail II dataset, which contains historical retail transactions from a UK-based online retailer. The dataset is used to explore how transactional data can support customer analytics and retention-related decisions within the proposed business scenario.

The project brings together SQL, Python, and Power BI to demonstrate an end-to-end data analytics workflow, from data preparation to customer-level analysis and interactive visualization.

Note: IKEA Gifting is the business case used for this project. The transaction data comes from the Online Retail II dataset and is not actual IKEA customer data.

## Business Objectives

1- Analyze customer purchasing behaviour and transaction patterns.

2- Segment customers based on Recency, Frequency, and Monetary value (RFM).

3- Identify potentially inactive customers using a 90-day inactivity threshold.

4- Understand customer value and purchasing patterns.

5- Present customer analytics through an interactive Power BI dashboard.

## Tools & Technologies

Tool

Purpose

MySQL Workbench

Data inspection, cleaning, and transformation

Python

Customer-level analysis and RFM segmentation

Pandas

Data manipulation and analysis

Power BI

Interactive dashboard development

DAX

Analytical measures and calculations

Dataset

The project uses the Online Retail II dataset, covering transactions from December 2009 to December 2011.

The dataset contains more than one million transaction records, including:

Invoice number

Stock code and product description

Quantity purchased

Invoice date

Unit price

Customer ID

Country

These fields provide the foundation for analyzing transaction patterns and customer purchasing behaviour.

Project Workflow

1. Data Loading and SQL Preparation

Loaded two CSV files into MySQL and combined their records into a single raw table. The data was then inspected and prepared for analysis, with attention to data quality and appropriate data types.

2. RFM Analysis Using Python

Used Python and Pandas to analyze customer purchasing behaviour through three metrics:

Recency: The number of days since a customer's most recent purchase.

Frequency: The number of distinct purchase transactions made by a customer.

Monetary: The total monetary value of a customer's purchases.

These metrics provide a structured approach to comparing customers based on their purchasing behaviour.

3. Customer Segmentation

Used RFM analysis to categorize customers according to their purchasing patterns and value.

The segmentation framework includes categories such as Champions, Loyal Customers, At Risk, New Customers, Needs Attention, and Lost Customers.

These categories help organize customer information into groups that can be examined for potential engagement and retention opportunities.

4. Churn Analysis

Used a fixed 90-day inactivity threshold to flag customers who had not purchased within the defined period.

This provides a basis for identifying potentially inactive customers and examining customer retention patterns.

5. Power BI Dashboard

Developed an interactive Power BI dashboard to present the customer analytics in a visual format.

The dashboard brings together relevant customer and transaction metrics to make the analysis easier to explore and interpret.

Key Learnings

Through this project, I gained practical experience in:

Working with a large transactional dataset.

Using SQL for data inspection and preparation.

Applying RFM methodology to customer analytics.

Using Python and Pandas for data manipulation and customer-level analysis.

Developing interactive dashboards in Power BI.

Using analytical results to explore business questions related to customer value and retention.

Conclusion

This project helped me strengthen my understanding of the data analytics workflow, from working with raw transactional data to analyzing customer behaviour and presenting the results through a dashboard.

It also provided an opportunity to connect technical skills with a business problem, focusing on how customer analytics can support more informed decisions around customer value and retention.

Project Status

Completed as part of my continued development in data analytics, SQL, Python, and Power BI.

Author: Aryan Gupta
