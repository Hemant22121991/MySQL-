Atliq Hardware Business Insights

Atliq Hardware Business Insights is an analytics project for an imaginary leading computer hardware producer in India – Atliq Hardwares. The project focuses on leveraging SQL queries and stored procedures to provide valuable business insights and enable quick, data-informed decisions.

Table of Contents

* Project Overview

* Problem Statement

* Key Requirements

* Project Structure

* Getting Started

* SQL Queries & Stored Procedures

* Usage

* Future Enhancements

* License

* Contact
  
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Project Overview
  
This project provides a comprehensive analysis of the business data for Atliq Hardwares, focusing on key performance indicators such as market operations, product counts, manufacturing costs, customer discounts, gross sales, and quarterly sales metrics. The insights generated help the executive management to make quick and informed strategic decisions.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Problem Statement

Atliq Hardwares, one of the leading computer hardware producers in India with an international presence, faced challenges in extracting real-time insights to support decision-making. The project aims to address these challenges by analyzing a SQL database containing multiple tables (e.g., Customer, Product, Sales, and Fiscal Data) to answer various business-critical questions.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Key Requirements
  
The project addresses the following business questions using SQL queries and stored procedures:

* Market Analysis:

** List the markets in which customer "Atliq Exclusive" operates its business in the APAC region.

** Includes a stored procedure for additional customer and region-based insights.

* Product Analysis:

** Calculate the percentage increase in unique products in 2021 vs. 2020.

** Report unique product counts for each segment.

** Identify the segment with the most increase in unique products.

* Manufacturing Cost Analysis:

** Identify products with the highest and lowest manufacturing costs.

** Provide top/bottom N products using stored procedures.

* Customer Discounts & Sales Performance:

** Generate a report listing the top 5 customers in India with the highest average pre-invoice discount percentage for FY2021.

** Provide detailed monthly gross sales for the customer "Atliq Exclusive" to identify low and high-performing months.

** Includes stored procedures for further customizations based on different criteria (e.g., Customer, Platform, Channel).

* Quarterly Sales Analysis:

** Determine which quarter of 2020 recorded the maximum total sold quantity.

** A stored procedure is available for analyzing different fiscal years.

* Channel & Product Sales:

** Analyze which channel contributed the most to gross sales in FY2021, along with the percentage contribution.

** List the top 3 products in each division with high total sold quantity in FY2021.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Getting Started

* Prerequisites:

** Database Engine: Ensure you have a SQL database engine installed (e.g., MySQL, PostgreSQL, SQL Server) to run the provided SQL scripts.

** SQL Client Tool: Use tools like MySQL Workbench, pgAdmin, or SQL Server Management Studio.

** Git: For cloning and managing the repository.

** Basic SQL Knowledge: Understanding of SQL queries and stored procedures.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* SQL Queries & Stored Procedures

** Each requirement has an associated SQL query file to extract the relevant insights.

** Stored procedures are provided to add flexibility for generating additional insights based on parameters such as different fiscal years, customers, markets, or sorting criteria.

** The structure allows easy customization, extension, or integration with other reporting tools.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Usage

** Running Queries: Execute individual SQL query files to get the desired results.

** Using Stored Procedures: Call the stored procedures with the required parameters. For example:
{
CALL sp_customer_market_insights('Atliq Exclusive', 'APAC');
CALL sp_manufacturing_cost_insights(2021, 'top', 10);
}

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Customization: Modify the parameters and conditions in the SQL queries or stored procedures to fit new business requirements or insights.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

* Future Enhancements:
  
** Integration with BI Tools: Connect with business intelligence tools (like Tableau or PowerBI) for real-time dashboard visualizations.

** Enhanced Reporting: Develop more dynamic reporting modules to support additional dimensions like time-series analysis and predictive modeling.

** Automation: Schedule automated runs of stored procedures and export reports to CSV/Excel for further analysis.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*License
This project is open-sourced under the MIT License.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*Contact
For further information or contributions, please reach out to:

Hemant Mandge – Project Report By

Email: mandge.hemant@gmail.com
