🛍️ Customer Shopping Behavior Analysis

🧩 Overview

This project provides a comprehensive analysis of customer shopping behavior using real-world e-commerce data. It covers every stage of the analytics pipeline — from data exploration and cleaning in Python, SQL-based querying in PostgreSQL, and interactive visualization in Power BI — to derive actionable business insights.

The main objective is to understand customer purchase patterns, product performance, and key revenue drivers, enabling data-driven decision-making for marketing and sales teams.


🗂️ Dataset

File: customer_shopping_behavior.csv

Records: ~3,900 entries

Columns include:

customer_id – Unique customer identifier

gender – Male/Female

age_group – Categorized age brackets

item_purchased – Product name

category – Product category

purchase_amount – Total purchase value

discount_applied – Yes/No

review_rating – Customer rating (1–5 scale)

shipping_type – Standard or Express

subscription_status – Whether the customer is a subscriber

previous_purchases – Number of past purchases

Source: Simulated dataset for analytical learning and visualization purposes.


🧰 Tools & Technologies
Category	Tools Used
Programming & Analysis	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL
Query Language	SQL
Visualization	Power BI
Development	Jupyter Notebook
Connection	SQLAlchemy / psycopg2


🔍 Steps Followed

1️⃣ Data Loading & Inspection

Loaded the dataset in Python using Pandas.

Performed basic checks — shape, null values, and data types.

Explored summary statistics using df.describe().

2️⃣ Exploratory Data Analysis (EDA)

Visualized gender-wise spending, age distribution, and category-wise revenue.

Identified top products and peak purchase categories.

Detected outliers and missing data patterns.

3️⃣ Data Cleaning

Removed duplicates and handled missing values.

Converted data types where needed (e.g., ratings to numeric).

Standardized categorical fields for consistency.

4️⃣ SQL-Based Analysis in PostgreSQL

File: customer_behavior_sql_queries.sql

Key analytical questions addressed:

💰 Revenue by gender: Which gender contributes more to total revenue?

🎯 High-spending discount users: Who used discounts but spent above average?

⭐ Top-rated products: Which items received the best average review ratings?

🚚 Shipping type analysis: Compare average purchases between Standard and Express.

🧾 Subscriber analysis: Do subscribers spend more than non-subscribers?

💸 Discount rate by product: Identify products most often bought with discounts.

👥 Customer segmentation: Classify customers as New, Returning, or Loyal.

🛒 Top products per category: Top 3 items in each product category.

🔁 Repeat buyers vs. subscription: Relationship between repeat buying and subscriptions.

👶 Age-group revenue: Revenue contribution by age bracket.

5️⃣ Power BI Dashboard

File: customer_behavior_dashboard.pbix

Built a fully interactive dashboard featuring:

Bar Chart: Revenue by Product Category and Sales by Product Category

Donut Chart: Gender-wise Revenue Contribution

KPI Cards: Total Revenue, Average Purchase, Number of Customers

Filter Panels: Gender, Age Group, Subscription Status, and Shipping Type

The dashboard allows easy filtering and visual storytelling for business insights.


📈 Results & Insights

Female customers contribute slightly more to total revenue.

Subscribed customers spend more on average than non-subscribers.

Express shipping users have higher purchase amounts.

Loyal customers form a smaller group but generate a large portion of sales.

Discounted purchases are strongly correlated with higher product turnover.

Top-rated products belong mainly to the Electronics and Accessories categories.


⚙️ How to Run the Project
🧮 1. Clone this Repository

git clone https://github.com/yourusername/customer-behavior-analysis.git

cd customer-behavior-analysis

🐍 2. Run Python Analysis

pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

jupyter notebook Customer_Shopping_Behavior_Analysis.ipynb

🗄️ 3. Set Up PostgreSQL

Create a new database (e.g., customer_db)

Load the dataset using SQLAlchemy or pgAdmin

Run queries from customer_behavior_sql_queries.sql

📊 4. Open Power BI Dashboard

Launch Power BI Desktop

Open customer_behavior_dashboard.pbix

Ensure PostgreSQL connection settings match your local setup


🏁 Conclusion

This project showcases data analysis, SQL querying, and BI visualization skills—all essential for data analytics and business intelligence roles. It highlights the ability to transform raw data into insightful, visually compelling stories that support real-world decision-making.
