# Customer_Shopping_Behavior_Analysis

📘 Project Overview

This project explores customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The goal was to uncover spending trends, customer segments, and product insights to support data-driven business decisions.

📊 Dataset Summary

Rows: 3,900

Columns: 18

Main Features:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item, Category, Purchase Amount, Season, Size, Color

Behavioral Attributes: Discount Applied, Review Rating, Shipping Type, Purchase Frequency

Missing Values: 37 in review_rating (filled with median rating per category)

🧹 Exploratory Data Analysis (Python)

Performed with Pandas and NumPy:

Cleaned and standardized column names

Handled missing values

Created new columns:

age_group (binned age categories)

purchase_frequency_days (derived from timestamps)

Checked redundancy (promo_code_used dropped)

Loaded cleaned dataset into MySQL for analysis

🧠 Data Analysis (MySQL)

Conducted SQL-based exploration to answer 10 key business questions:

Revenue comparison by gender

High-spending discount users

Top 5 products by rating

Standard vs. Express shipping spend

Subscribers vs. non-subscribers

Discount-dependent products

Customer segmentation (New, Returning, Loyal)

Top 3 products in each category

Subscription likelihood of repeat buyers

Revenue by age group

📈 Power BI Dashboard

Developed an interactive Power BI dashboard featuring:

Revenue by demographics

Product performance visualization

Subscription and loyalty segmentation

Purchase trends by shipping and discount usage

💼 Business Recommendations

Increase Subscriptions: Offer member-only benefits

Loyalty Programs: Encourage repeat purchases

Discount Optimization: Protect profit margins

Product Focus: Highlight top-rated and best-sellers

Targeted Marketing: Focus on high-value demographics

🛠️ Tech Stack

Python, MySQL, Power BI, Pandas, Matplotlib, Seaborn
