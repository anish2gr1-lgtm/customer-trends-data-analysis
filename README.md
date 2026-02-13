## Project Overview
This project analyzes customer shopping behavior using transactional retail data to uncover insights into customer segments, spending patterns, product performance, and purchase drivers. The goal is to help businesses improve customer engagement, optimize marketing strategies, and increase revenue through data-driven decision making.

## Business Problem
Retail companies need to understand how customer demographics, discounts, subscriptions, and product preferences impact purchasing behavior. This project answers key business questions such as:
Which customers generate the most revenue?
How do discounts affect spending behavior?
What products and categories perform best?
How does subscription status influence customer loyalty?
Which customer segments should be targeted for growth?

## Dataset Information
Total Records: 3,900 transactions
Total Features: 18 columns

## Key Features:
Customer demographics (Age, Gender, Location)
Purchase details (Item, Category, Amount, Season)
Customer behavior (Subscription status, Discounts, Ratings)
Transaction attributes (Shipping type, Frequency)

## Tools & Technologies Used
Python (pandas, numpy) – Data cleaning and preprocessing
SQL (PostgreSQL) – Data analysis and business queries
Power BI – Data visualization and dashboard creation
GitHub – Project version control and documentation

## Project Workflow
## 1. Data Cleaning & Preparation (Python)
Loaded and explored dataset using pandas
Handled missing values using median imputation
Standardized column names
Created new features such as age groups and purchase frequency

## 2. Data Analysis (SQL)

Performed business analysis including:

Revenue analysis by gender and age group

Customer segmentation (New, Returning, Loyal)

Product performance and top-selling items

Discount impact on purchase behavior

Subscription vs non-subscription customer analysis

## 3. Dashboard Creation (Power BI)

Developed an interactive dashboard showing:

Total Customers

Average Purchase Amount

Revenue by Category

Customer Segments

Sales Trends

Subscription Analysis

## Key Insights

Loyal customers contribute the highest revenue

Express shipping customers spend more on average

Certain products perform better with discount strategies

Subscription customers show higher engagement and retention

Specific age groups contribute more to total revenue

## Business Recommendations

Target loyal and high-value customers with personalized offers

Promote subscription programs to increase retention

Focus marketing on high-performing products and categories

Optimize discount strategies for maximum revenue impact

Use customer segmentation for targeted marketing campaigns

## Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer behaviour sql queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
│
└── README.md

## Dashboard Preview

Power BI dashboard includes:

KPI cards

Revenue analysis

Customer segmentation

Category performance

Interactive filters

## How to Run This Project

Clone the repository

git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git


Open Jupyter Notebook and run:

Customer_Shopping_Behavior_Analysis.ipynb


Run SQL queries in PostgreSQL

Open Power BI dashboard file:

customer_behavior_dashboard.pbix

Skills Demonstrated

Data Cleaning

Exploratory Data Analysis

SQL Querying

Data Visualization

Dashboard Development

Business Analysis

Data-driven decision making# customer-trends-data-analysis
