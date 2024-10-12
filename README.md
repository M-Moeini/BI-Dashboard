# Sales Insights Dashboard - Power BI & Tableau

This project provides detailed business intelligence insights into the sales of a branch shop operating across multiple markets. The insights are derived from a sales database containing customer information, transaction records, market names, and product details.

## Project Overview

The purpose of this project is to help the business make informed decisions by visualizing key sales metrics such as revenue trends, top-performing customers, and products. The analysis was performed using both Power BI and Tableau to deliver a comprehensive and interactive dashboard.

## Technologies Used

- **SQL**: Used to extract and transform data from the sales database.
- **Power BI**: For building interactive dashboards, performing detailed data analysis, and visualizing insights.
- **Tableau**: For an alternative, more visual representation of the same data, providing flexibility for stakeholders.
- **ETL**: Data was extracted, transformed, and loaded into Power BI and Tableau for analysis.


## Dashboard Previews

### Power BI Dashboard
[![Power BI Dashboard Preview](https://github.com/M-Moeini/BI-Dashboard/blob/main/PowerBI/PowerBI.png)](https://github.com/M-Moeini/BI-Dashboard/issues/1)



### Tableau Dashboard
[![Tableau Dashboard Preview](https://github.com/M-Moeini/BI-Dashboard/blob/main/Tableau/Tableau.png)](https://github.com/M-Moeini/BI-Dashboard/issues/4)




### ETL Process

An ETL (Extract, Transform, Load) process was implemented to prepare the data for analysis:
- **Extract**: Data was extracted from the SQL database containing sales transactions, customer information, market details, and product records.
- **Transform**: The data was cleaned, transformed, and aggregated to remove inconsistencies, handle missing values, and format it for business intelligence analysis. Key transformations included:
   - Formatting dates for time-based analysis
   - Calculating revenue and sales quantities based on transactions
   - Merging tables to create a unified dataset for visualizations
- **Load**: The cleaned and transformed data was loaded into both Power BI and Tableau for building the dashboards and creating visual insights.

## Data Source

The sales database contains the following information:
- **Customers:** Customer Code, Customer Name, Customer Type
- **Transactions:** Order Date, Sales Quantity, Sales Amount, Product Code, Market Code, Customer Code, Currency
- **Markets:** Market Code, Market Name
- **Products:** Product Code, Product Type

You can find the SQL dump of the database [here](https://github.com/codebasics/DataAnalysisProjects/blob/master/2_SalesInsightsTableau/db_dump.sql).

## Key Metrics and Visualizations

1. **Revenue Trend by Time**  
   Displays the total revenue generated over time (monthly) to help identify patterns and seasonality.

2. **Revenue by Market (Ascending Order)**  
   Shows revenue distribution across different markets, helping to identify which markets perform better or need improvement.

3. **Sales Quantity by Market (Ascending Order)**  
   Displays the total number of products sold per market in ascending order.

4. **Top 5 Customers by Revenue**  
   Lists the top 5 customers who contributed the most revenue, offering insights into customer value.

5. **Top 5 Products by Revenue**  
   Highlights the top 5 products that generated the most revenue.



## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com//M-Moeini/BI-Dashboard.git
   
