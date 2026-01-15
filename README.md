 Customer Behavior Analysis – Data Analytics Project
 Overview :
This project analyzes customer purchasing behavior to understand how demographics, shopping patterns, and promotional strategies influence buying decisions.
The analysis combines Python, SQL, and Power BI to explore customer trends, measure key performance indicators (KPIs), and build an interactive dashboard for business insights.
 Dataset 
Source: Customer Behavior Dataset
Rows: 3,900
Columns: 18
Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior:
Discount Applied
Promo Code Used
Previous Purchases
Purchase Frequency
Review Rating
Shipping Type
Data Quality:
Missing Values: 37 missing entries in the Review Rating column
Missing values were handled during preprocessing to ensure accurate analysis.

Tools & Technologies

Python: Pandas, NumPy, Matplotlib
Jupyter Notebook: Data cleaning and exploratory data analysis (EDA)
SQL: PostgreSQL / MySQL / SQL Server
Power BI: Interactive dashboard creation
Excel: Supporting analysis and validation

 Project Workflow / Steps
1️ Data Loading & Exploration (Python)
Loaded the dataset into Jupyter Notebook using Pandas
Inspected data structure, data types, and summary statistics
Identified missing values in the Review Rating column

2️ Data Cleaning & Preparation
Handled missing values in Review Rating to maintain analysis consistency
Standardized column names for cross-tool compatibility
Verified data consistency across demographic and purchase-related fields

3️ Exploratory Data Analysis (EDA)
Analyzed customer demographics and purchase patterns
Explored relationships between discounts, subscriptions, and purchase amount
Studied rating distribution and customer satisfaction trends

4️ Data Analysis Using SQL
Imported the cleaned dataset into a relational database
Executed SQL queries to calculate KPIs such as:
Number of Customers
Average Purchase Amount
Average Review Rating
Performed segmentation analysis based on gender, subscription status, category, and shipping type

5️ Dashboard Development (Power BI)
Built an interactive Power BI dashboard to visualize customer behavior
KPIs:
Total Number of Customers
Average Review Rating
Average Purchase Amount
Visuals Used:

Donut & Pie Charts:
Subscription Status Distribution
Shipping Type Usage

Column Charts:
Purchase Amount by Category
Customer Count by Gender

Filters / Slicers:
Gender
Subscription Status
Shipping Type
Product Category

 Dashboard Highlights

Clear visibility into customer purchasing patterns
Interactive filters to explore different customer segments
Insights into how subscriptions and promotions affect spending
Easy-to-understand visuals for business stakeholders

 Key Results & Insights
 
Identified high-value customer segments based on subscription status
Observed differences in purchasing behavior across genders and categories
Analyzed the impact of shipping type and promotions on customer satisfaction
Provided actionable insights to improve customer engagement and retention
