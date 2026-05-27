# 🛒 Business Intelligence Sales Performance Dashboard

![Power BI Dashboard](Project_1.png)

## 📌 Project Overview

The **Business Intelligence Sales Performance Dashboard** is an interactive and data-driven Power BI project designed to analyze and monitor overall business performance through key sales and profitability metrics. The dashboard provides actionable insights into sales trends, customer behavior, regional performance, product profitability, shipping patterns, and return analysis.

This project helps business stakeholders make informed decisions by transforming raw sales data into visually appealing and meaningful reports.

The dashboard was built using **Power BI**, leveraging **DAX calculations**, interactive slicers, KPIs, and advanced visualizations for enhanced business intelligence reporting.

---

# 🎯 Project Objectives

The main objectives of this project are:

- To analyze overall business sales and profitability
- To identify top-performing and underperforming products
- To monitor customer segment behavior
- To track profit trends across regions
- To analyze product return patterns
- To understand shipping and delivery performance
- To build a fully interactive business dashboard for stakeholders

---

# 📊 Dashboard Pages

The dashboard consists of two fully interactive pages.

---

# 📄 Dashboard Page 1 — Sales & Profit Analysis

![Dashboard Overview](Project_1.png)

This page focuses on:

- Sales Performance
- Profit Analysis
- KPI Monitoring
- Customer Segment Insights
- Product Category Analysis

---

## 🔹 Key KPIs Included

| KPI | Description |
|------|-------------|
| Total Sales | Overall revenue generated |
| Total Profit | Net profit earned |
| Total Orders | Total number of orders placed |
| Profit Margin (%) | Overall profitability percentage |
| Average Order Value | Average revenue per order |

---

## 📈 Visualizations Used

### 1️⃣ Sales Growth Analysis Over Time

- Displays yearly sales trends
- Compares customer segments:
  - Consumer
  - Corporate
  - Home Office
- Helps identify business growth patterns

---

### 2️⃣ Profit Trend Across Regions by Segment

Analyzes:

- Regional profitability
- Segment-wise contribution
- High and low-performing regions

Regions included:

- West
- East
- South
- Central

---

### 3️⃣ Segment-wise Profit Margin Distribution

A donut chart showing:

- Profit contribution by customer segment
- Comparative segment performance

---

### 4️⃣ Top-Selling Products by Sales Value

Highlights products generating maximum revenue.

Top products include:

- Phones
- Chairs
- Storage
- Tables
- Binders

---

### 5️⃣ Category-wise Sales vs Profit Comparison

Compares:

- Total Sales
- Total Profit

Across categories:

- Technology
- Furniture
- Office Supplies

---

# 📄 Dashboard Page 2 — Returns & Shipping Analysis

![Detailed Dashboard](Project_2.png)

This page provides detailed operational insights.

---

## 🔍 Key Insights Covered

- Product Return Analysis
- Customer Return Behavior
- Delivery Performance
- Shipping Analysis
- Sub-category Level Sales & Profit Data

---

## 📊 Visualizations Included

### 1️⃣ Most Frequently Returned Products

Displays products with highest return rates.

Products analyzed:

- Machines
- Fasteners
- Appliances
- Tables
- Supplies
- Phones

This helps businesses identify:

- Product quality issues
- Customer dissatisfaction trends
- Operational challenges

---

### 2️⃣ Total Return Orders by Customer Segment

Analyzes return behavior among:

- Consumer
- Corporate
- Home Office

Useful for:

- Customer retention analysis
- Service quality improvements

---

### 3️⃣ Orders Distributed by Delivery Time

Tracks:

- Delivery duration
- Order distribution trends
- Logistics efficiency

---

### 4️⃣ Sales Distribution by Ship Mode

Compares sales generated through:

- Standard Class
- Second Class
- First Class
- Same Day

Helps identify:

- Preferred shipping methods
- Shipping performance trends

---

### 5️⃣ Sub-Category Matrix Table

Detailed matrix showing:

- Sales
- Profit
- Discount

Across sub-categories like:

- Chairs
- Copiers
- Phones
- Binders
- Appliances

---

# 📌 Interactive Features

The dashboard contains multiple interactive features for better user experience.

## ✅ Dynamic Filters (Slicers)

Users can filter reports based on:

- Year
- Region
- Category
- Segment

These filters dynamically update all visuals in real time.

---

# 🎨 Dashboard Design Features

## ✔ Clean UI Design

- Minimal and professional layout
- Balanced color palette
- Easy navigation

## ✔ Visual Hierarchy

Important KPIs are highlighted using:

- Cards
- Color indicators
- Data labels

## ✔ Interactive Navigation

- Drill-through capability
- Detailed analysis page
- Responsive slicers

---

# 📈 Business Insights Derived

The dashboard helps derive several important business insights.

## 🔹 Sales Insights

- Consumer segment contributes the highest sales
- Technology category generates maximum revenue
- Phones and Chairs are top-selling products

---

## 🔹 Profit Insights

- West region performs strongly in profitability
- Certain sub-categories show high sales but low profit
- Discount-heavy products reduce profitability

---

## 🔹 Return Insights

- Machines and Fasteners have higher return percentages
- Return behavior varies significantly by customer segment

---

## 🔹 Shipping Insights

- Standard Class shipping contributes the highest sales
- Delivery time impacts customer satisfaction and returns

---

# 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard Development |
| DAX | Data Modeling & Measures |
| Microsoft Excel | Data Source |
| Power Query | Data Cleaning & Transformation |

---

# 📂 Dataset Information

The dataset includes:

- Orders Data
- Sales Data
- Profit Data
- Customer Segment Information
- Shipping Details
- Product Categories
- Regional Information
- Returns Data

---

# 🧮 DAX Measures Used

Some important DAX calculations used in the project:

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
```

---

# 🚀 Project Workflow

## Step 1 — Data Collection

Collected raw sales and order data from Excel.

---

## Step 2 — Data Cleaning

Performed:

- Null value handling
- Data formatting
- Relationship building

Using Power Query.

---

## Step 3 — Data Modeling

Created:

- Relationships
- Measures
- Calculated columns
- KPIs using DAX

---

## Step 4 — Dashboard Development

Designed:

- Interactive visuals
- KPI cards
- Filters
- Navigation buttons

---

## Step 5 — Insight Generation

Analyzed:

- Sales trends
- Customer behavior
- Product performance
- Return patterns

---

# 📌 Dashboard Advantages

✅ Easy to understand  
✅ Interactive reporting  
✅ Business decision support  
✅ Real-time filtering  
✅ Professional dashboard design  
✅ Performance tracking  
✅ Operational analysis  

---

# 📷 Additional Dashboard Screenshots

## Furniture Category Analysis

![Furniture Analysis](Project_3.png)

---

## Furniture Detailed Insights

![Furniture Detailed Analysis](Project_4.png)

---

# 💡 Future Improvements

Future enhancements planned:

- Integration with SQL Database
- Real-time data refresh
- Forecasting & predictive analytics
- AI-powered insights
- Mobile dashboard optimization
- Advanced drill-through pages

---

# 👩‍💻 Author

## **Nicky Kumari**

### 📌 Skills

- Power BI
- Data Visualization
- DAX
- Excel
- Business Intelligence
- Dashboard Development

---

# ⭐ GitHub Repository

If you found this project useful, feel free to:

⭐ Star the repository  
🍴 Fork the project  
📥 Download and explore  

---

# 📬 Contact

For collaboration or feedback:

- LinkedIn: *Add Your LinkedIn Profile*
- Email: *Add Your Email Address*

---

# 📄 License

This project is created for educational and portfolio purposes.

---

# 🙌 Thank You

Thank you for visiting this project repository.  
Your feedback and suggestions are always appreciated.
