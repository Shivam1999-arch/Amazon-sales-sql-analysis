**🛒 Amazon Sales Data Analysis (SQL Project)**
📌 Overview

This project analyzes Amazon sales data from three cities/branches in Myanmar — Yangon, Mandalay, and Naypyitaw — for the first quarter of 2019 (January–March 2019). The dataset contains 1000 rows and 17 columns, covering invoice-level sales transactions.

The goal is to derive business insights around sales performance, customer behavior, product trends, and revenue contribution using SQL.

**🎯 Objectives**
Analyze overall sales performance of Amazon
Identify top-performing and low-performing product lines
Study customer behavior based on gender and customer type
Analyze sales trends over time (monthly, daily, hourly)
Calculate total revenue, COGS, and gross income
Derive key business insights for decision-making

**🛠️ Tools & Technologies Used**
MySQL (Database)
MySQL Workbench
SQL (Structured Query Language)
CSV Dataset

**🔧 Project Workflow**
Data Wrangling – Created database, imported dataset, checked for null values and datatypes
Feature Engineering – Added time_of_day, day_name, and month_name columns from date/time fields
Exploratory Data Analysis – Created a cleaned amazon_sales table with proper datatypes and constraints
Business Question Analysis – Answered 28 business questions using SQL queries (aggregations, subqueries, CTEs, window-style logic)

**📊 Key Findings**
Product Analysis

Highest Sales (units): Electronic Accessories (971 units)
Highest Revenue: Food and Beverages ($56,144.96)
Lowest Sales & Revenue: Health and Beauty

Sales Analysis

Highest Revenue Month: January ($116,292.11)
Highest Revenue Branch/City: Naypyitaw [Branch C] ($110,568.86)
Peak Sales Time: Afternoon
Peak Sales Day: Saturday

Customer Analysis

Predominant Gender: Female
Predominant Customer Type: Member
Highest Revenue Gender: Female ($167,883.26)
Highest Revenue Customer Type: Member ($164,223.81)

📁 Repository Structure
├── README.md
├── Amazon_Sales_Data_SQL_Project.sql   # Full SQL script (data wrangling, EDA, business questions)
├── docs/
│   └── Amazon_Sales_Presentation.pdf   # Project presentation slides

**🚀 How to Use**
Clone this repository
Import the dataset into MySQL Workbench using the Table Data Import Wizard
Run Amazon_Sales_Data_SQL_Project.sql step by step
Explore the 28 business questions and their query solutions

**🔮 Future Scope**
Integration with visualization tools like Power BI or Tableau
Advanced analysis using CTEs and window functions
Predictive analysis using historical sales data
Automated reporting dashboards
