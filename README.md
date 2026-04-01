🛒 E-commerce Sales & Customer Behavior Analysis using RFM Segmentation

📌 Overview

This project performs an end-to-end analysis of an e-commerce (Superstore) dataset to uncover key business insights related to sales performance and customer behavior. It includes data cleaning, exploratory data analysis (EDA), and advanced customer segmentation using RFM (Recency, Frequency, Monetary) analysis, along with an interactive Power BI dashboard.

🎯 Objectives

* Analyze overall sales performance across categories, regions, and products
* Identify top-performing products and high-revenue segments
* Understand customer purchasing behavior
* Segment customers using RFM analysis
* Provide actionable business insights for revenue growth

🧰 Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Power BI (Dashboard & Data Modeling)
* Excel (Data Handling)
* DAX (Data Analysis Expressions)

---

📂 Dataset

* Superstore Sales Dataset (`train.csv`)
* Contains:

  * Order details (Order ID, Order Date, Ship Date)
  * Customer information (Customer ID, Segment, Region)
  * Product details (Category, Sub-Category, Product Name)
  * Sales metrics (Sales, Quantity, Profit)


⚙️ Project Workflow

1. Data Cleaning

* Converted date columns to datetime format
* Handled missing values
* Verified data consistency

2. Exploratory Data Analysis (EDA)

* Sales trends over time
* Top-performing products
* Category-wise and region-wise sales
* Customer segment analysis

3. Customer Segmentation (RFM Analysis)

* **Recency:** Days since last purchase
* **Frequency:** Number of purchases
* **Monetary:** Total spending

Customers were segmented into:

* High Value
* Medium Value
* Low Value


📊 Power BI Dashboard

🔹 Sales Dashboard

* KPI Cards: Total Sales, Orders, Customers, AOV
* Sales Trend (Monthly)
* Sales by Category & Region
* Top Products & Cities

🔹 RFM Dashboard

* Customer Segment Distribution
* Revenue by Segment
* RFM Scatter Plot (Frequency vs Monetary)
* Recency Distribution (Histogram)

 📈 Key Insights

* A small percentage of customers contribute the majority of revenue
* Technology category generates the highest sales
* Western region shows strong performance
* High-value customers purchase frequently and spend more
* Certain cities dominate sales, indicating expansion opportunities

💡 Business Recommendations

* Focus on retaining high-value customers through loyalty programs
* Upsell to medium-value customers to increase revenue
* Improve performance of low-performing categories
* Run targeted campaigns based on customer segments
* Expand in high-performing regions and cities

📁 Project Structure
Ecommerce-Analysis/
│
├── data/                # Dataset
├── notebooks/           # Python analysis
├── dashboard/           # Power BI file (.pbix)
├── images/              # Dashboard screenshots
└── README.md

🧠 Learning Outcomes

* Hands-on experience with real-world data analysis
* Built interactive dashboards using Power BI
* Applied RFM segmentation for customer analytics
* Generated business insights from raw data
