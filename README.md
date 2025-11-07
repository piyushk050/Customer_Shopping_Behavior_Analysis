# Customer_Shopping_Behavior_Analysis


📘 Project Overview

This project explores customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The goal was to uncover spending trends, customer segments, and product insights to support data-driven business decisions.



📊 Dataset Summary

1. Rows: 3,900

2. Columns: 18

3. Main Features:

4. Demographics: Age, Gender, Location, Subscription Status

5. Purchase Details: Item, Category, Purchase Amount, Season, Size, Color

6. Behavioral Attributes: Discount Applied, Review Rating, Shipping Type, Purchase Frequency

7. Missing Values: 37 in review_rating (filled with median rating per category)



🧹 Exploratory Data Analysis (Python)

Performed with Pandas and NumPy:

1. Cleaned and standardized column names

2. Handled missing values


Created new columns:

1. age_group (binned age categories)

2. purchase_frequency_days (derived from timestamps)
 
3. Checked redundancy (promo_code_used dropped)

4. Loaded cleaned dataset into MySQL for analysis



🧠 Data Analysis (MySQL)

Conducted SQL-based exploration to answer 10 key business questions:

1. Revenue comparison by gender

2. High-spending discount users

3. Top 5 products by rating

4. Standard vs. Express shipping spend

5. Subscribers vs. non-subscribers

6. Discount-dependent products

7. Customer segmentation (New, Returning, Loyal)

8. Top 3 products in each category

9. Subscription likelihood of repeat buyers

10. Revenue by age group

    

📈 Power BI Dashboard

Developed an interactive Power BI dashboard featuring:

1. Revenue by demographics
 
2. Product performance visualization

3. Subscription and loyalty segmentation

4. Purchase trends by shipping and discount usage

   

💼 Business Recommendations

1. Increase Subscriptions: Offer member-only benefits

2. Loyalty Programs: Encourage repeat purchases

3. Discount Optimization: Protect profit margins

4. Product Focus: Highlight top-rated and best-sellers

5. Targeted Marketing: Focus on high-value demographics

   

🛠️ Tech Stack

- Python, MySQL, Power BI, Pandas, Matplotlib, Seaborn
