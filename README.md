# customer-shopping-analysis
Using retail data to find trends in customer spending, subscriptions, and ratings. Built using Python, PostgreSQL, and Power BI.

# Customer Shopping Behavior Analysis 

[cite_start]This project analyzes a dataset of 3,900 customer purchases across different product categories[cite: 3]. [cite_start]It covers data cleaning in Python, running database queries in SQL, and building an interactive dashboard in Power BI to understand how people shop[cite: 13, 26, 77].

##  Project Overview
[cite_start]The main goal of this project is to figure out patterns in customer spending, age groups, product preferences, and subscription status to help a business make smarter decisions[cite: 4, 22].

##  Tools Used
* [cite_start]**Python (Pandas):** For data cleaning and preparation[cite: 14, 15].
* [cite_start]**PostgreSQL:** For querying the clean data and answering business questions[cite: 25, 27].
* [cite_start]**Power BI:** For building an interactive visual dashboard[cite: 76, 77].

##  Dataset Summary
* [cite_start]**Total Rows:** 3,900 purchases [cite: 3]
* [cite_start]**Columns:** 18 features (including Age, Gender, Purchase Amount, Subscriptions, and Ratings) [cite: 6, 7, 9, 10, 11]
* [cite_start]**Data Cleaning:** Handled 37 missing review ratings by filling them with the median rating for that product category[cite: 12, 19]. [cite_start]Also dropped redundant promo code columns and grouped ages into segments[cite: 22, 24].

---

##  Key Insights from SQL

* [cite_start]**Gender Spending:** Male customers generated more total revenue (\$157,890) compared to Female customers (\$75,191)[cite: 34, 37].
* [cite_start]**Top Category:** Clothing is the most purchased product category[cite: 17].
* [cite_start]**Subscriptions:** Out of the repeat buyers, 2,518 are not subscribed, while 958 are subscribed[cite: 59]. This is a huge opportunity for a loyalty program!
* [cite_start]**Age Groups:** Young Adults bring in the highest total revenue (\$62,143), followed closely by Middle-aged customers[cite: 65, 66, 68].

---

## 📈 Dashboard Preview
*(Take a screenshot of your Power BI dashboard, name the file `dashboard.png`, upload it to this GitHub repository, and it will show up below!)*

![Customer Behavior Dashboard](dashboard.png)

### Core Metrics Tracked:
* [cite_start]**Total Customers:** 3.9K [cite: 82]
* [cite_start]**Average Purchase:** \$59.76 [cite: 84]
* [cite_start]**Average Rating:** 3.75 [cite: 86]

---

## 💡 Quick Recommendations
1. [cite_start]**Target Unsubscribed Regulars:** Create a small discount campaign aimed at the 2,518 repeat buyers who aren't subscribers yet to convert them[cite: 59, 114].
2. [cite_start]**Watch the Discounts:** Items like Hats and Sneakers have very high discount rates (~50%)[cite: 52]. [cite_start]Balance these to keep profit margins healthy[cite: 118].
3. [cite_start]**Focus on Young Adults:** Put more marketing effort into the Young Adult age group since they are your biggest revenue drivers[cite: 65, 66, 120].
