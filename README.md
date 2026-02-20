# 🛒 Supermarket Sales Analysis — Power BI Dashboard

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** built on historical sales data from a supermarket chain operating across **3 branches** over a **3-month period (January–March 2019)**. The goal is to uncover actionable insights around customer behavior, product performance, payment preferences, and satisfaction levels.

---
## DashBoard- 
<img width="1337" height="745" alt="Snapshot_Heart_Disease" src="https://github.com/AritraBanerjee-09/SuperMarket-Sales/blob/23850d2c5e3a64957907a973ef6254bc6ba57913/BI%20image.jpg" />
## 📊 Dataset Description

The dataset contains transactional records from 3 supermarket branches (A, B, C) located in different cities.

| Column | Description |
|---|---|
| Invoice ID | Unique computer-generated sales slip ID |
| Branch | Branch identifier (A, B, or C) |
| City | City where the branch is located |
| Customer Type | Member (loyalty card) or Normal |
| Gender | Customer's gender |
| Product Line | Category: Electronics, Fashion, Food & Beverages, Health & Beauty, Home & Lifestyle, Sports & Travel |
| Unit Price | Price per product (USD) |
| Quantity | Number of units purchased |
| Tax (5%) | Tax applied to the purchase |
| Total | Total price including tax |
| Date | Date of transaction |
| Time | Time of transaction (10 AM – 9 PM) |
| Payment | Method: Cash, Credit Card, or E-wallet |
| COGS | Cost of Goods Sold |
| Gross Margin % | Gross margin percentage |
| Gross Income | Income after COGS |
| Rating | Customer satisfaction rating (1–10) |

---

## 🔍 Key Findings

### 👥 Customer Demographics
- Total customers: **1,000** — Male: **499**, Female: **501** (nearly equal split)

### 💰 Sales Performance
| Metric | Value |
|---|---|
| Total Sales (incl. tax) | $322.97K |
| Total Sales (excl. tax) | $307.59K |
| Total Tax Collected | $15.38K |

### ⏰ Peak Shopping Hours
- Sales peak between **2 PM and 3 PM**

### 🛍️ Product Line Insights
- **Female customers** spend more on: Fashion Accessories, Food & Beverages, Sports & Travel
- **Male customers** spend more on: Electronic Accessories
- **Top 3 product lines by sales:** Food & Beverages, Sports & Travel, Electronic Accessories
- **Bottom 3 product lines by sales:** Fashion Accessories, Home & Lifestyle, Health & Beauty

### 💳 Payment Methods
- Most used: **E-wallet** and **Cash**, followed by **Credit Card**

### ⭐ Customer Satisfaction
| Satisfaction Level | Percentage |
|---|---|
| Good (moderate) | 42.6% |
| Best (high) | 40.0% |
| Bad (low) | 17.4% |

> Over **82%** of customers reported a good or excellent experience.

---

## 🛠️ Tools Used

- **Power BI Desktop** — Dashboard design and data visualization
- **Microsoft Excel / CSV** — Data source

---

## 📁 Repository Structure

```
supermarket-sales-powerbi/
│
├── README.md
├── dataset/
│   └── supermarket_sales.csv
└── dashboard/
    └── Supermarket_Sales.pbix
```

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/supermarket-sales-powerbi.git
   ```
2. Open `Supermarket_Sales.pbix` in **Power BI Desktop**
3. If needed, update the data source path to point to `dataset/supermarket_sales.csv`
4. Explore the interactive dashboard

---

## 📌 Dataset Source

The dataset is publicly available on [Kaggle — Supermarket Sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales).

---

## 🙋 Author

**Aritra Banerjee**
[LinkedIn](https://www.linkedin.com/in/aritra-banerjee-/) • [GitHub](https://github.com/AritraBanerjee-09)

---

> ⭐ If you found this project helpful, consider giving it a star!
