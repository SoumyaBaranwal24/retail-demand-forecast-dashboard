# Retail Demand Forecast & Inventory Dashboard

An interactive Power BI dashboard that analyzes 4 years of retail sales data to forecast future demand and surface the insights a store manager would need for inventory planning.

![Dashboard Overview](screenshots/overview.png)

## 📊 Overview

Retailers lose revenue two ways: running out of stock loses sales, and overstocking locks up cash. This project turns historical sales data into a forward-looking dashboard that helps answer: what sold, what's selling best, and what to expect next.

## 🎯 Objective

- Analyze 4 years of historical sales data (2015–2018)
- Forecast demand for the next 3 months using statistical modeling
- Identify top-performing categories, regions, cities, and sub-categories
- Support inventory and reorder decisions with a single, decision-ready dashboard

## 🗂️ Dataset

- **Source**: [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) (Kaggle)
- **Size**: 9,800 records
- **Period**: 2015 – 2018
- **Fields used**: Order Date, Category, Sub-Category, Region, City, Sales, Order ID

## 🛠️ Tools Used

- **Microsoft Excel** — data inspection and the FORECAST function
- **Microsoft Power BI Desktop** — dashboard build, DAX aggregations, and forecasting

## 📈 Dashboard Features

| Visual | Description |
|---|---|
| KPI Cards | Total Sales, Total Orders, Top Category, Top Region, Forecasted Next Month, Top City |
| Monthly Sales Trend & Forecast | Line chart with a 3-month forecast and confidence interval |
| Sales by Category | Column chart comparing Technology, Furniture, and Office Supplies |
| Sales by Region | Donut chart showing East/West/Central/South split |
| Sales by City | Bar chart of top-selling cities |
| Category → Sub-Category Funnel | Funnel chart ranking top sub-categories by sales |

## 🔑 Key Insights

- **Technology** is the top-performing category (₹8.27L in sales)
- **West** is the top-performing region (31.4% of total sales)
- **New York** is the highest-selling city
- **Phones** and **Chairs** are the strongest individual sub-categories
- Next month's sales are forecasted at **₹40,843** (95% confidence range: ₹21,241 – ₹60,446)

## 📂 Repository Contents

```
├── Retail_Demand_Forecast_Dashboard.pbix   # Power BI dashboard file
├── screenshots/                            # Dashboard preview images
└── README.md
```

## ▶️ How to Open

1. Download `Retail_Demand_Forecast_Dashboard.pbix`
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
3. If prompted, allow data refresh — the dataset is embedded, so no external connection is needed

## 👤 Author

**Soumya Baranwal**
B.Tech Computer Engineering, ABES Engineering College, Ghaziabad
[LinkedIn](https://linkedin.com/in/soumyabaranwaljavadeveloper/)

*Built as part of an HCL training program.*
