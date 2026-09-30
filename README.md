# E-Commerce Product & Customer Analytics

## Project Overview
An interactive Power BI analytics dashboard built to analyze e-commerce sales,
customer purchasing behavior, product performance, and geographic revenue contribution.

## Business Objective
The objective of this project is to help business and product teams understand:
- How revenue changes over time
- Which countries contribute the most revenue
- Which products generate the highest revenue
- How many customers make repeat purchases
- Key sales and customer performance indicators

## Tools & Technologies
- Power BI
- DAX
- Power Query
- Excel

## Data Preparation
The transaction data was cleaned and transformed using Power Query.

Key preparation steps included:
- Correcting data types
- Removing cancelled transactions
- Removing non-positive quantities
- Removing zero/negative unit-price transactions
- Creating a Revenue column using Quantity × Unit Price
- Creating Month-Year fields for time-series analysis

## Key KPIs
| KPI | Value |
|---|---:|
| Total Revenue | 10.67M |
| Total Orders | 20K |
| Total Customers | 4K |
| Average Order Value | 534.40 |
| Repeat Customer Rate | 65.6% |

## Analysis Performed
- Monthly revenue trend analysis
- Top 10 countries by revenue
- Top 10 products by revenue
- Customer repeat-purchase analysis
- KPI development using DAX
- Interactive country filtering
- Interactive date filtering

## Dashboard
The Power BI dashboard combines sales, customer, product, and geographic
analysis into a single interactive business reporting view.

## Project Outcome
The dashboard provides a consolidated view of business performance and
customer behavior that can be used to identify revenue trends, major markets,
high-performing products, and repeat-purchase behavior.
