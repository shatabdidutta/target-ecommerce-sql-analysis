# target-ecommerce-sql-analysis
📊 Target E-commerce SQL Analysis
📌 Project Overview

This project performs an end-to-end exploratory and analytical study of a Brazilian e-commerce dataset using SQL (BigQuery). The objective is to derive actionable business insights by analyzing customer behavior, order trends, regional performance, delivery efficiency, and payment patterns.

🎯 Objectives
Understand overall business growth and order trends
Identify seasonal and time-based purchasing behavior
Analyze regional distribution of customers and orders
Evaluate pricing, freight costs, and revenue movement
Assess delivery performance and logistics efficiency
Study customer payment preferences and installment behavior
🗂 Dataset Description

The dataset consists of 8 CSV files:

customers.csv
geolocation.csv
orders.csv
order_items.csv
payments.csv
reviews.csv
products.csv
sellers.csv

These datasets were joined and analyzed to simulate real-world e-commerce business scenarios.

⚙️ Tools & Technologies
SQL (Google BigQuery) – Data querying and analysis
CSV Files – Raw dataset
GitHub – Version control and project hosting
🔍 Key Analysis Performed
1. Exploratory Data Analysis
Checked data types and schema structure
Identified order time range (2016–2018)
Counted unique cities and states
2. Order Trends & Seasonality
Strong growth observed from 2016 → 2018
Monthly seasonality identified (peak in early months)
Time-of-day analysis:
Afternoon & Night = highest orders
Dawn = lowest activity
3. Regional Analysis
Customers distributed across all 27 states
Top states by customer base: SP, RJ, MG
State-wise order distribution highlights growth opportunities
4. Revenue & Cost Analysis
138.53% increase in order value (2017 → 2018, Jan–Aug)
State-wise:
High total revenue in SP
Variation in average order value across states
5. Logistics & Delivery Performance
Delivery time calculated per order
Identified delays and early deliveries
Key findings:
Some states face logistical inefficiencies
Others show strong delivery performance (competitive advantage)
6. Freight Analysis
Significant variation in shipping costs across states
High freight regions indicate:
Longer distances OR
Inefficient logistics
7. Payment Behavior Analysis
Multiple payment methods used:
Credit cards (dominant)
Vouchers, UPI, debit cards
Installment analysis shows customer preference for flexible payments
📈 Key Insights
Rapid business growth indicates strong market expansion
Demand is seasonal and time-dependent
Certain states dominate revenue and customer base
Logistics performance varies significantly across regions
Customers prefer afternoon/night shopping and flexible payments
🚀 Business Recommendations
Focus on high-performing states (SP, RJ, MG) for revenue growth
Improve logistics in high-delay regions to enhance customer satisfaction
Introduce targeted discounts in low-demand months
Optimize shipping routes to reduce freight costs
Promote EMI / installment options for high-value purchases
Run marketing campaigns during peak hours (afternoon & night)
📂 Project Structure
target-ecommerce-sql-analysis/
│
├── data/
├── sql/
├── outputs/
│   └── screenshots/
├── docs/
└── README.md
📸 Sample Outputs

(Screenshots of query results are available in the outputs/screenshots/ folder)

💡 Conclusion

This project demonstrates how SQL can be used to extract meaningful insights from raw e-commerce data and translate them into strategic business decisions. It reflects real-world analytical thinking applicable to roles in data analytics, business intelligence, and product strategy.

🧠 Author

Shatabdi Dutta
