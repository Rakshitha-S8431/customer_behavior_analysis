# customer_behavior_analysis
End-to-end data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI to generate actionable business insights.
Project Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, and product preferences. The goal is to support data-driven business decisions through data analysis and visualization.

🛠️ Tech Stack
Python (Pandas, NumPy) – Data cleaning & preprocessing
SQL (PostgreSQL / MySQL / SQL Server) – Data analysis
Power BI – Dashboard & visualization
📂 Project Workflow
1. Data Loading & Cleaning (Python)
Loaded dataset using Pandas
Performed data inspection using .info() and .describe()
Handled missing values (imputed missing ratings)
Standardized column names (snake_case)
Created new features:
Age groups
Purchase frequency
Removed redundant columns
2. Data Analysis (SQL)

Executed SQL queries to answer key business questions:

Revenue analysis by gender
High-spending customers using discounts
Top-rated and best-selling products
Shipping type comparison
Subscriber vs non-subscriber behavior
Customer segmentation (New, Returning, Loyal)
Revenue contribution by age group
3. Data Visualization (Power BI)
Built an interactive dashboard
Visualized key metrics:
Revenue trends
Customer segments
Product performance
Purchase behavior patterns
📊 Key Insights
Identified high-value customer segments
Found top-performing products and categories
Analyzed impact of discounts on revenue
Observed differences in subscriber vs non-subscriber spending
💡 Business Recommendations
Promote subscription programs to increase retention
Introduce customer loyalty rewards
Optimize discount strategies for profitability
Focus marketing on high-revenue segments
📁 Project Structure
├── data/                # Raw & cleaned datasets
├── notebooks/           # Python analysis scripts
├── sql/                 # SQL queries
├── dashboard/           # Power BI file
└── README.md
🚀 How to Run
Load dataset in Python (Pandas)
Perform data cleaning and preprocessing
Export cleaned data to SQL database
Run SQL queries for analysis
Connect Power BI to database and build dashboard
📌 Conclusion

This project demonstrates end-to-end data analytics skills — from data cleaning and SQL analysis to dashboard creation — making it a strong showcase of practical data analytics capabilities.
