# E-Commerce C2C User Analysis

📍 **SQL File Link:** [View File]() 

## Project Overview
This project analyzes an E-commerce Customer-to-Customer (C2C) platform using a dataset (users_data.csv) containing 98,913 rows and 27 columns. The goal is to explore user behavior, platform adoption, and country-level insights using SQL queries.

## 📝 Key Tasks & Queries

**🔹 Setup**
- Created new schema ecommerce.
- Imported users_data.csv into MySQL.
- Explored structure using DESC and initial SELECT queries.

**🔹 Exploratory Queries**

- First 100 rows preview.
- Count of distinct countries and languages.
- Gender comparison: Who has more followers (Male vs Female)?

**🔹 Platform Usage**

- Count of users with profile pictures.
- Users with app installed (Any App, Android, iOS).

**🔹 Buyer & Seller Insights**

- Buyers by country (descending order).
- Sellers by country (ascending order).
- Top 10 countries by product pass rate.

**🔹 Language & Gender Behavior**

- Users grouped by language choice.
- Female preferences: wishlist vs product likes.
- Male preferences: buyer vs seller activity.

**🔹 Country-Level Trends**

- Country with maximum buyers.
- Countries with zero sellers.
- Distribution of male & female users per country.

**🔹 User Activity**

- Top 110 most recently active users.
- Female users inactive for >100 days.

**🔹 Product Transactions**

- Average products sold/bought by male users per country.

## 📊 Insights

- ✅ Male vs Female Followers: SQL analysis checked which gender has more total followers.
- ✅ App Usage: Significant portion of users access via Android/iOS apps.
- ✅ Buyer-Seller Distribution: Clear country-level differences in products bought vs sold.
- ✅ Engagement: Female users tend to wishlist or socially like products; male users show stronger buy/sell behavior.
- ✅ Activity Trends: Some users inactive for 100+ days highlight churn risk.
- ✅ Market Potential: Certain countries have zero sellers but active buyers — untapped opportunity.

## 🛠 Tools & Skills

- SQL (MySQL) → Schema creation, Joins, Aggregations, Group By, Union, Ordering, Limits.
- Dataset → users_data.csv with ~99k rows, 27 columns.
- Focus → User segmentation, country-level insights, buyer vs seller trends.

