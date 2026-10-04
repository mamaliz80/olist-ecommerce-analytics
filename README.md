# Olist E-Commerce Analytics

A Power BI portfolio project analyzing Brazilian e-commerce data from the Olist dataset.

The project focuses on sales performance, customer behavior, product categories, reviews, delivery performance, and operational KPIs.

## 📊 Dashboard

The Power BI dashboard contains five pages:

* **Overview** — Executive KPIs and monthly sales trends
* **Sales & Products** — Sales by product category, customer state, seller state, AOV, and freight costs
* **Customers & Reviews** — Customer behavior, review scores, repeat customers, and day-of-week analysis
* **Delivery & Operations** — Order status, delivery performance, late orders, and delivery time
* **Executive Summary** — High-level management view of the most important KPIs and sales trends

## 🎯 Business Questions

This project explores questions such as:

* How are sales changing over time?
* Which product categories generate the most sales?
* Which Brazilian states contribute the most revenue?
* How significant are freight costs?
* How frequently do customers make repeat purchases?
* How do customers rate their shopping experience?
* How does delivery performance relate to review scores?
* How often are orders delivered late?
* How long does an average order take to reach the customer?

## 🛠️ Tools & Technologies

* **Power BI** — Data modeling, DAX, interactive dashboard and visualization
* **Power Query** — Data preparation and transformation
* **DAX** — KPI and analytical measure creation
* **Python** — Exploratory data analysis
* **Pandas / NumPy** — Data analysis and validation
* **Matplotlib / Seaborn** — Exploratory visualization

## 🗂️ Data Model

The Power BI model uses a dimensional structure with fact and dimension tables.

### Fact Tables

* orders_fact
* order_items_fact
* reviews_fact

### Dimension Tables

* customers_dim
* products_dim
* sellers_dim
* calendar_dim

The model connects orders, customers, products, sellers, reviews, and calendar data to support interactive analysis.

## 📈 Key KPIs

Some of the main KPIs included in the dashboard are:

* Total Sales
* Total Orders
* Average Order Value (AOV)
* Total Freight
* Unique Customers
* Average Review Score
* Five-Star Review Rate
* Late Order Rate
* Average Delivery Days

## 🔎 Key Insights

The analysis identified several notable patterns:

* Olist processed approximately **99K orders**.
* More than **96K unique customers** are represented in the dataset.
* Approximately **97% of orders were delivered**.
* Around **7.9% of orders were delivered later than the estimated delivery date**.
* Approximately **3.1% of customers made repeat purchases**, indicating a strong opportunity for customer retention.
* Five-star reviews represented approximately **58% of reviewed orders**.
* Delivery performance is strongly associated with customer satisfaction: orders delivered on time received substantially higher average review scores than late orders.
* **Health & Beauty, Watches & Gifts, Bed & Bath Table, and Sports & Leisure** were among the strongest product categories by sales.

## 📁 Project Structure

text
olist-ecommerce-analytics/
│
├── Olist_Dashboard.pbix
├── README.md
└── screenshots/
    ├── overview.png
    ├── sales_products.png
    ├── customers_reviews.png
    ├── delivery_operations.png
    └── executive_summary.png

## 📌 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**, originally published on Kaggle.

The original dataset contains information about orders, customers, products, sellers, payments, reviews, and geolocation.

## 👤 Author

**Mohamad**

This project was created as part of a data analytics portfolio to demonstrate practical skills in Power BI, DAX, data modeling, Python, and business analysis.
