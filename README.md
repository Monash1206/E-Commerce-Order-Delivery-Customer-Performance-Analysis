# E-Commerce-Order-Delivery-Customer-Performance-Analysis

📌 Project Overview
This project analyzes a multi-table e-commerce dataset to evaluate order lifecycle performance, delivery efficiency, customer behavior, seller performance, product performance, payments, and customer satisfaction.
The objective is to simulate a real-world Business Analytics scenario where an e-commerce company wants to identify operational inefficiencies, improve delivery performance, understand customer behavior, benchmark sellers, and support data-driven decision-making.
The project uses SQL as the primary analysis tool, with the results designed to support an executive dashboard in Power BI / Tableau / Excel.

🎯 Business Problem
E-commerce platforms depend on customers, sellers, logistics, products, and payment systems working together efficiently.
Problems such as:
- Delivery delays
- Order cancellations
- Poor seller performance
- Low customer satisfaction
- Weak customer retention
- Uneven product/category performance
can directly affect revenue and customer experience.
This analysis answers the central business question:
Where are inefficiencies occurring, and what actions can be taken to improve e-commerce performance?

🎯 Business Objectives
- Improve delivery performance and reduce delays
- Measure order fulfillment efficiency
- Identify high-performing and underperforming sellers
- Analyze product category demand and revenue
- Understand customer geographic distribution
- Analyze payment behavior
- Measure customer satisfaction
- Understand the relationship between delivery and reviews
- Identify repeat customers
- Detect high-risk customer experiences
- Provide an executive-level performance summary

🧰 Tools & Skills
Tools
- MySQL 8+
- Power BI / Tableau / Excel
- GitHub
Skills Demonstrated
- SQL Joins
- CTEs
- Subqueries
- Aggregate Functions
- Window Functions
- CASE Statements
- Date & Time Analysis
- Data Validation
- Data Cleaning
- KPI Development
- Time-Series Analysis
- Customer Analysis
- Seller Performance Analysis
- RFM Segmentation
- Business Insight Generation
- Dashboard Storytelling

🗂️ Dataset Structure
The analysis uses eight relational tables:
Table	Description
orders	Order lifecycle from purchase through delivery
order_items	Product and seller details for each order
customers	Customer ID, unique customer ID, city and state
products	Product category and physical attributes
sellers	Seller location information
payments	Payment type, installments and transaction value
reviews	Customer review scores
geolocation	Geographic mapping information

📊 Key KPIs
The project evaluates:
- Total Orders
- Delivered Orders %
- Cancelled Orders %
- Average Delivery Time
- On-Time Delivery Rate
- Total Revenue
- Average Order Value
- Average Review Score
- Repeat Customer Rate

  
🔎 SQL Analysis Performed
1. Overall Order Operations Health Check
Measures total orders, delivered orders, cancelled orders, and average order value.
2. Order Lifecycle Performance
Analyzes the distribution of orders across delivered, shipped, cancelled, and other statuses.
3. Delivery Time Analysis
Calculates average, minimum, and maximum delivery duration.
4. Delivery Delay Analysis
Identifies orders delivered after their estimated delivery date and calculates the delay rate.
5. Seller Performance Benchmarking
Compares sellers using:
- Total orders
- Average delivery time
- Average review score
6. Customer Distribution & Demand
Identifies cities and states generating the highest customer and order volumes.
7. Product Category Performance
Measures:
- Order volume
- Items sold
- Product revenue
- Freight value
- Gross item value
8. Payment Behavior
Analyzes payment methods, transaction value, revenue contribution, and installments.
9. Customer Satisfaction
Analyzes the distribution of review scores.
10. Delivery vs Customer Satisfaction
Tests whether longer or late deliveries are associated with lower review scores.
11. Order Value & Revenue
Compares revenue and average order value across product categories.
12. Time-Based Order Trends
Analyzes monthly orders, revenue, and month-over-month growth.
13. Customer Retention
Uses customer_unique_id to distinguish repeat customers from one-time buyers.
14. High-Risk Orders
Identifies orders with both long delivery durations and poor review scores.
15. Executive Performance Summary
Combines major KPIs into one decision-ready output.


🚀 Advanced SQL Analysis
RFM Customer Segmentation
Customers are evaluated using:
- Recency — How recently the customer purchased
- Frequency — How often the customer purchased
- Monetary — How much the customer spent
Example segments include:
- Champions
- Loyal Customers
- New / Promising
- Potential Loyalists
- At Risk
- Lost / Hibernating
Seller Revenue Ranking
Uses SQL window functions to rank sellers by revenue.
State-Level Delivery Performance
Compares geographic markets using:
- Delivered orders
- Average delivery time
- On-time delivery rate
- Average review score

  
📈 Dashboard Plan
An executive Power BI/Tableau dashboard can be organized into four pages.
Page 1 — Executive Overview
KPI Cards
- Total Orders
- Total Revenue
- Average Order Value
- On-Time Delivery %
- Average Review Score
Charts
- Monthly Order Trend
- Order Status Distribution
- Monthly Revenue Trend
Page 2 — Delivery & Operations
- Average Delivery Time
- On-Time vs Late Orders
- Delivery Performance by State
- Delivery Time vs Review Score
- High-Risk Orders
Page 3 — Customer & Product
- Customer Distribution by State
- Top Product Categories
- Category Revenue
- Repeat vs One-Time Customers
- RFM Customer Segments
Page 4 — Seller Performance
- Top Sellers by Revenue
- Seller Order Volume
- Seller Average Delivery Time
- Seller Average Review Score

  
💡 Business Insights to Derive
After running the SQL against the dataset, the analysis should identify:
1. Which stages of the order lifecycle create operational bottlenecks.
2. Which regions experience the highest demand and delivery challenges.
3. Which product categories contribute the most orders and revenue.
4. Which sellers combine high order volume with strong customer satisfaction.
5. Whether late deliveries are associated with lower review scores.
6. Which customers show repeat purchasing behavior.
7. Which customer segments deserve retention or re-engagement campaigns.
8. Which high-risk orders require root-cause analysis.
Important: Replace these with your actual numerical findings after running the SQL. Do not add made-up results to the portfolio.
