# IKEA-RFM-Project-Practice-Project-
**Tools & Technologies:** MySQL | Python | Pandas | Power BI | DAX

## Project Overview

This project focuses on customer purchasing behaviour, customer segmentation, and potential churn through an IKEA Gifting customer analytics business case.

The analysis uses the **Online Retail II dataset**, which contains historical transactions from a UK-based online retailer between December 2009 and December 2011. The objective is to explore how transactional data can be used to understand customer behaviour and support customer retention decisions.

The project combines SQL, Python, and Power BI to demonstrate an end-to-end data analytics workflow, from data preparation to customer-level analysis and interactive visualization.

> **Note:** IKEA Gifting is the business case used for this project. The dataset contains transactions from a UK-based online retailer and is not actual IKEA customer data.

## Business Objectives

- Analyze customer purchasing behaviour and transaction patterns.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Identify potentially inactive customers using a 90-day inactivity threshold.
- Understand customer value and purchasing patterns.
- Present the analysis through an interactive Power BI dashboard.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL Workbench | Data inspection, cleaning, and transformation |
| Python | Customer-level analysis and RFM segmentation |
| Pandas | Data manipulation and analysis |
| Power BI | Interactive dashboard development |
| DAX | Analytical measures and calculations |

## Dataset

The project uses the **Online Retail II dataset**, which contains more than one million transaction records.

The dataset includes the following fields:

- Invoice number
- Stock code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

These fields provide the foundation for analyzing transaction patterns and customer purchasing behaviour.

## Project Workflow

### 1. Data Loading and SQL Preparation

Loaded two CSV files into MySQL and combined their records into a single raw table. The data was then inspected and prepared for analysis, with attention to data quality and appropriate data types.

### 2. RFM Analysis Using Python

Used Python and Pandas to analyze customer purchasing behaviour through three metrics:

- **Recency:** Number of days since a customer's most recent purchase.
- **Frequency:** Number of distinct purchase transactions made by a customer.
- **Monetary:** Total monetary value of a customer's purchases.

These metrics provide a structured approach to evaluating customer purchasing behaviour.

### 3. Customer Segmentation

Applied RFM analysis to categorize customers according to their purchasing patterns and value.

The segmentation framework includes categories such as:

- Champions
- Loyal Customers
- At Risk
- New Customers
- Needs Attention
- Lost Customers

These segments help organize customer information and explore potential customer engagement and retention opportunities.

### 4. Churn Analysis

Used a fixed 90-day inactivity threshold to flag customers who had not purchased within the defined period.

This analysis provides a starting point for identifying potentially inactive customers and examining customer retention patterns.

### 5. Power BI Dashboard

Developed an interactive Power BI dashboard to present customer analytics in a visual format.

The dashboard brings together relevant customer and transaction metrics to make the analysis easier to explore and interpret.

## Key Learnings

Through this project, I gained practical experience in:

- Working with a large transactional dataset.
- Using SQL for data inspection and preparation.
- Applying RFM methodology to customer analytics.
- Using Python and Pandas for data manipulation and customer-level analysis.
- Developing interactive dashboards in Power BI.
- Connecting technical analysis with business questions related to customer value and retention.

## Conclusion

This project strengthened my understanding of the data analytics workflow, from raw data preparation to customer segmentation and dashboard development.

It also helped me connect technical skills with a business problem and explore how customer analytics can support more informed decisions around customer value and retention.

## Project Status

Completed as part of my continued development in data analytics, SQL, Python, and Power BI.

---

**Author:** Aryan Gupta















