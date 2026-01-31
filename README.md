# 🛒 E-Commerce Sales EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on an online retail dataset to uncover key patterns in **sales performance, product revenue concentration, geographic distribution, and transaction behavior**.  
The goal is to derive **actionable business insights** that support data-driven decision-making.

---

## 📂 Dataset
- **Source:** UK Online Retail Dataset  
- **Time Period:** December 2010 – December 2011  
- **Business Type:** UK-based non-store online retailer selling unique all-occasion gift items  
- **Customer Base:** Mix of retail customers and wholesalers  

### Key Fields
- Invoice Number  
- Product Description  
- Quantity  
- Unit Price  
- Customer ID  
- Invoice Date  
- Country  

> ⚠️ *The dataset is not included in this repository due to licensing considerations.*

---

## 🔧 Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical analysis
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook** – analysis environment

---

## 🧹 Data Cleaning & Preparation
The dataset was cleaned and prepared by:
- Removing cancelled and invalid transactions
- Excluding records with missing customer identifiers
- Filtering out zero or negative quantities and prices
- Converting invoice dates to datetime format
- Removing duplicate records
- Creating derived features such as **Revenue**, **Year**, and **Month**

---

## 📊 Key Insights

### 📈 Sales Trend Over Time
Sales remain relatively stable during the first half of the year, followed by a sharp increase from **September to November**, indicating strong **seasonal and holiday-driven demand**. The slight decline in December is likely due to incomplete data rather than an actual reduction in sales.

---

### 🏆 Top Products by Revenue
Revenue is highly concentrated among a small set of products, with items such as **“Paper Craft, Little Birdie”** and **“Regency Cakestand 3 Tier”** contributing disproportionately to total revenue. This highlights opportunities for **focused inventory planning and targeted promotions**.

---

### 🌍 Country-wise Revenue Distribution
The **United Kingdom** overwhelmingly dominates total revenue, reflecting the company’s primary market. Other countries contribute significantly smaller shares, suggesting potential opportunities for **international market expansion**.

---

### 💰 Average Order Value (AOV)
The average order value of **$479.56** indicates that transactions are typically **high-value**, consistent with bulk or wholesale purchasing behavior. This presents opportunities for **bundling strategies and volume-based pricing**.

---

### 🧺 Basket Size (Items per Invoice)
Basket size distribution is highly right-skewed. While the mean basket size is elevated due to extreme bulk orders, the **median basket size of 154 items** provides a more accurate representation of a typical transaction. This reinforces the wholesale-oriented nature of the business.

---

## ✅ Final Conclusion
The analysis reveals a business model driven by **seasonal demand, bulk purchasing, and revenue concentration among key products**. Strong Q4 performance underscores the importance of holiday-driven sales, while high order values and large basket sizes confirm the significance of wholesale transactions. These insights can inform **sales planning, product strategy, and market expansion decisions**, demonstrating the value of leveraging transactional data for strategic business insights.

---

## ▶️ How to Run
1. Clone the repository  
2. Open the Jupyter notebook  
3. Ensure required libraries are installed  
4. Run all cells sequentially  

---

## 📌 Author
**Manas Mishra**  
Data Analysis & Data Science Enthusiast
