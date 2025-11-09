# customer_behavior_analysis
This project analyzes customer shopping data from 3,900 transactions across multiple product categories to uncover valuable business insights. Using Python, SQL, and Power BI, the analysis focuses on identifying spending patterns, customer segments, product preferences, and subscription trends.

📘 Overview

This project explores customer shopping behaviour using transactional data from 3,900 purchases across different product categories.
The goal is to understand spending habits, customer segments, product preferences, and subscription patterns.
By combining Python, SQL, and Power BI, this analysis provides data-driven insights to help improve marketing, retention, and sales strategies.

📊 Dataset

Total Records: 3,900

Columns: 18

Key Features:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Colour

Shopping Behaviour: Discount Applied, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

Missing Data: 37 missing values in the Review Rating column

🧰 Tools and Technologies

Python: Data loading, cleaning, and exploratory data analysis (EDA)

MySQL / PostgreSQL: Running business queries and structured data analysis

Power BI: Creating interactive dashboards and visual reports

Gamma App: Designing the final project presentation

Libraries Used: pandas, numpy, matplotlib, seaborn, sqlalchemy

🧩 Steps Followed
1. Data Loading

Imported the dataset into Python using pandas.

Checked the structure using df.info() and viewed summary statistics with df.describe().

2. Data Cleaning

Handled missing values by imputing median ratings by category.

Standardized column names to snake_case for consistency.

Removed redundant columns such as duplicate promo code fields.

3. Exploratory Data Analysis (EDA)

Analysed spending patterns across gender, age group, and location.

Explored relationships between discounts, product categories, and ratings.

Created new features like age_group and purchase_frequency_days.

4. SQL Analysis

Loaded the cleaned dataset into a MySQL database.

Wrote queries to answer business questions, such as:

Revenue by gender and age group

High-spending discount users

Top-rated and most-purchased products

Subscription impact on total revenue

Comparison of express vs. standard shipping

5. Dashboard Creation (Power BI)

Built an interactive dashboard to visualize key insights.

Included visuals for revenue trends, customer segmentation, and top product categories.

6. Reporting and Presentation

Compiled findings into a detailed written report.

Designed a professional presentation using Gamma to summarize key insights and recommendations.

📈 Dashboard and Results

Key Insights:

Female customers contributed slightly higher revenue overall.

Subscribers showed greater purchase frequency and total spend.

Discount usage did not always correlate with lower spending — some high-value customers still used discounts.

Top-rated products were also among the best-selling ones.

Express shipping customers tend to have higher purchase amounts.

💡 Business Recommendations

Increase Subscriptions: Offer personalized perks for members.

Enhance Loyalty Programs: Reward frequent customers to encourage repeat purchases.

Optimize Discount Strategies: Balance discount offers with profit margins.

Promote Bestsellers: Feature top-rated and high-selling products in campaigns.

Targeted Marketing: Focus efforts on high-revenue customer segments and locations.

📦 Folder Structure
Customer_Shopping_Behaviour_Analysis/
│
├── data/                  # Raw and cleaned datasets  
├── notebooks/             # Python scripts and Jupyter notebooks  
├── sql_queries/           # SQL scripts for analysis  
├── dashboard/             # Power BI dashboard files  
├── report/                # Final report and Gamma presentation  
└── README.md              # Project documentation  

🧠 Conclusion

This project combines data analysis, SQL querying, and visualization to provide meaningful insights into customer shopping behaviour.
The approach demonstrates how structured data exploration and visualization can guide better business decisions.
