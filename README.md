# Amazon-Sales-Analysis-Dashboard
Power BI Dashboard 

# 📊 Amazon Sales Analytics Dashboard

Tools: Power BI, SQL, DAX, Power Query, Python (Pandas)

# 📌 Project Overview

This project analyzes Amazon product sales data to uncover revenue trends, customer behavior, product performance, and regional insights. An interactive Power BI dashboard was created to help stakeholders monitor KPIs and make data-driven business decisions.

# 📁 Dataset Summary

The dataset includes:

OrderID, OrderDate

CustomerID, CustomerName

ProductID, ProductName

Category, Brand

Quantity, Unit Price, Discount, Tax

Shipping Cost, Total Amount

Payment Method, Order Status

City, State, Country

Seller ID

# 🔧 Key Features

Interactive dashboard to track sales, profit, orders, and customer metrics

Dynamic filters for category, brand, city, state, seller, and date range

Drill-down visuals for product-wise and region-wise analysis

KPI cards for Total Revenue, AOV, Profit Margin, Return Rate

SQL queries for data extraction and transformation

DAX measures to build calculated fields and business KPIs

# 📈 Insights Uncovered

Electronics and Fashion categories dominate total revenue

Tier-1 cities drive most sales and customer traffic

COD remains the most preferred payment method

Moderate discounts correlate with higher profit margins

Weekends show significantly higher order volume

# 🧠 Skills Demonstrated

Data cleaning & transformation using Python and Power Query

Data modeling and relationship design in Power BI

Writing advanced SQL for aggregation and business logic

Creating DAX measures for KPIs

Building professional, user-friendly dashboards

# 📎 Project Structure
├── /Data                # Source and cleaned datasets  
├── /Dashboard           # Power BI .pbix file  
├── README.md            # Project documentation  
└── /Images              # Dashboard screenshots  

# 🚀 Outcome

A complete analytics solution enabling Amazon stakeholders to:

Monitor performance in real time

## I asked Chatgpt "pretend you are the manager of amazon and I'm a data analyst and ask me questions about the data to find insights and patterns"

# 🛒 Round 1 — Data Quality & Understanding

Do we have missing values in critical columns such as Unit Price, Quantity, Tax, Discount, Total Amount, or Order Status?

Are there any duplicate orders based on OrderID or CustomerID?

How many total orders and unique customers are present in the dataset?

# 📦 Round 2 — Sales Performance

Which product categories generate the highest Total Revenue?

Which brands contribute the most to our sales volume and revenue?

What is the average order value (AOV) across the dataset?

Are there seasonal patterns—do sales peak in certain months?

# 👥 Round 3 — Customer Insights

Who are our top 10 customers based on total spending?

What is the customer retention rate—how many customers purchase multiple times?

Do customers from certain cities or states purchase more frequently or spend more?

# 🚚 Round 4 — Operational Insights

Which payment methods are most used?

What percentage of orders are Cancelled / Returned / Delivered?

Do certain sellers have more delivery failures, delays, or returns?

# 💸 Round 5 — Pricing & Profitability

Which products have the highest profit margins (Unit Price – Discount – Tax – ShippingCost)?

Are discount-heavy products actually creating more sales or hurting margins?

Is there a relationship between Unit Price and Quantity sold?

Are higher-priced items selling less or more?

# 🌍 Round 6 — Geographic Trends

Which cities, states, or countries generate the most revenue?

Are there regions where certain categories perform significantly better or worse?

# 🏷️ Round 7 — Category & Brand Behavior

Which categories have the highest return/cancellation rates?

Which brands have the best repeat-buy rates?

# 📊 Round 8 — Advanced Patterns

Can we identify frequently bought together products (market basket analysis)?

Which customers are at risk of churn based on declining purchase frequency?

What is the lifetime value (CLV) of our high-value customers?

# 🎯 Round 9 — Strategic Questions

If we increase discount by 5%, how will it impact sales of top categories?

Can we recommend best-performing sellers to feature on homepage banners?

Where should we invest more:

high-selling categories

fast-growing categories

high-margin categories?

Identify high-performing categories and brands

Improve pricing, discount, and regional strategies

Understand customer purchase patterns
