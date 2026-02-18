# 📊 Magnus Sales Analysis – End-to-End Python Project

Comprehensive sales analysis project using Python (Pandas & Matplotlib) to transform multi-table transactional data into structured insights on revenue, demand, profitability, returns, and customer behavior.

---

## 📌 Project Objective

Analyze the Magnus sales dataset to:

- Understand revenue growth trends
- Identify top-performing products and categories
- Evaluate geographic performance
- Examine return patterns
- Assess demand seasonality
- Derive actionable business insights

---

## 🧹 Data Preparation & Engineering

The dataset consisted of multiple relational tables including:

- Calendar
- Customers
- Products
- Product Categories
- Product Subcategories
- Sales (2015–2017)
- Returns
- Territories

### Key Data Engineering Steps

- Concatenated multi-year sales data (2015–2017)
- Converted date columns to datetime format
- Created derived time features:
  - Year
  - Month
  - Quarter
- Performed multi-table merges using foreign keys
- Validated duplicates and missing values
- Engineered key financial metrics:
  - **Revenue = Quantity × Product Price**
  - **Profit = (Price − Cost) × Quantity**
  - Customer Age (from birthdate)

This created a unified analytical dataset suitable for EDA.

---

## 📈 Exploratory Data Analysis

### 1️⃣ Yearly Revenue Trend

- Strong growth from 2015 to 2016
- Continued but slower growth in 2017

Indicates successful early expansion followed by stabilization.

---

### 2️⃣ Monthly Seasonality Analysis

- Clear seasonal patterns in both revenue and demand
- Certain months consistently outperform others
- Demand spikes do not always translate proportionally to revenue

Highlights pricing and margin effects.

---

### 3️⃣ Category Performance

Top Revenue Categories:

- Furniture (highest contributor)
- Toys & School Supplies
- Jewellery (lower relative contribution)

Shows concentration of revenue in select product segments.

---

### 4️⃣ Top Products by Revenue

- A small number of products contribute disproportionately to total revenue
- Clear revenue concentration effect (Pareto-like distribution)

Indicates importance of premium or high-performing SKUs.

---

### 5️⃣ Geographic Performance (Country-Level)

Revenue distribution shows concentration in a few key markets:

- United States (largest contributor)
- Australia
- United Kingdom
- Canada
- Germany
- France

Business performance heavily depends on specific geographic regions.

---

### 6️⃣ Return Analysis

- Identified most returned products
- High return quantity impacts net profitability
- Certain product categories (e.g., Toys & School Supplies) show higher return frequency

Suggests potential quality control or demand mismatch issues.

---

### 7️⃣ Demand Analysis (Quantity Sold)

- Identified high-demand products
- High-demand products are not always highest-revenue items
- Demonstrates price × volume dynamics

---

### 8️⃣ Gender-Based Revenue Distribution

- Revenue analyzed by customer gender
- Female customers generated slightly higher revenue contribution

---

## 🔍 Key Business Insights

- Revenue growth stabilized after strong initial expansion
- Sales show clear seasonal patterns
- Revenue concentration exists across both products and countries
- High demand does not automatically imply high profitability
- Returns affect category-level performance and require strategic control
- Geographic concentration increases regional risk exposure

---

## 🛠 Skills Demonstrated

- Python (Pandas, NumPy)
- Data Cleaning & Transformation
- Multi-table Data Merging
- Revenue & Profit Calculation
- Exploratory Data Analysis (EDA)
- Trend Analysis
- Seasonality Detection
- Revenue Concentration Analysis
- Return & Demand Evaluation
- Data Visualization (Matplotlib)

---

## 🎯 Conclusion

This project demonstrates a complete analytical workflow:

Raw Relational Data → Cleaning & Feature Engineering → Financial Metric Calculation → EDA → Business Insight Extraction

It reflects structured analytical thinking and the ability to convert multi-source sales data into decision-oriented business insights using Python.
