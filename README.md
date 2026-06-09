# 📊 Quoodo Sales Analytics Dashboard

A comprehensive 3-page **Power BI dashboard** built for **Quoodo.com**, covering Revenue, Product, and Customer analytics with interactive filters and rich visualizations.

---

## 🔍 Overview

| Metric | Value |
|---|---|
| Total Orders | 25K |
| Gross Revenue | 3.56M |
| Net Revenue | 3.20M |
| Total Customers | 22K |
| Revenue Growth % | 3.87 |

---

## 📄 Dashboard Pages

### Page 1 — Quoodo Dashboard (Sales Overview)
The main landing page with high-level KPIs and cross-category insights.

- **Revenue Trend Line Chart** — Monthly revenue tracking across the full year
- **Top 10 Products** — Horizontal bar chart ranked by sales amount (Peanut Butter, Strawberry Jam, Rice Flour leading)
- **Sales by Country Map** — Geographic distribution of sales across continents
- **Category-wise Revenue Donut** — Breakdown across Beverages, Snacks, Pickles, Essentials, and Spreads
- **Order Status Analysis** — Visual breakdown of Delivered, Pending, Cancelled, Returned, and Shipped orders

**Filters:** Year/Month, Category, Country, Payment Method, Product Name

---

### Page 2 — Product Analysis
Deep-dive into product performance, return rates, and spending patterns.

- **Key Metrics:** Cancellation Rate (0.20), Delivery Success Rate (0.20), Return Rate (0.20)
- **Global Revenue Performance** — 527.27K vs goal of 4122 (+12691.51%)
- **Order ID Count by Customer Rating** — Donut chart showing near-equal distribution across all 5 ratings
- **Average Spending by Month** — Trend line showing spending stability (~125–130 range)
- **Return Orders by Category** — Pickles and Spreads lead in returns (~985 and ~983)
- **Sum of Final Amount by Product Name** — Top revenue products: Nachos, Ginger Garlic Paste, Popcorn, Wheat Flour
- **Product Performance Distribution** — Scatter plot of Revenue vs Quantity by Category

**Filters:** Country, Order Status, Customer Rating, Category

---

### Page 3 — Customer Analysis
Customer retention, spending behavior, and geographic distribution.

- **Customer Retention & Rating Analysis** — Average rating 2.83, Goal: 14769 (-99.98%)
- **Key KPIs:** Total Customers (22K), Repeat Customers (2K), One-Time Customers (20K), Top Customers Revenue (15.39K), Average Spending ($127.99)
- **Customer Spending Trend** — Monthly average spending chart (~125–130 range year-round)
- **Top Customers** — Michael S. leads at 2.4K, followed by David Smith (1.7K) and Michael Jo. (1.6K)
- **Ratings Distribution** — Near-uniform distribution across ratings 1–5 (~5K each)
- **Country-wise Customers** — Geographic map showing customer spread (Middle East, India, Australia, Africa)
- **80% gauge** — Customer satisfaction/retention indicator

**Filters:** Customer Rating, Country, Category, Customer Name

---

## 🛠️ Tools & Technologies

- **Tool:** Microsoft Power BI Desktop
- **Data Source:** Quoodo.com sales data
- **Visuals Used:** Line charts, bar charts, donut charts, maps, KPI cards, gauge charts, scatter plots, treemaps

---

## 📁 File Structure

```
quoodo-sales-dashboard/
├── README.md
├── Quoodo new.pbix          # Main Power BI file
└── screenshots/
    ├── page1-overview.png
    ├── page2-product.png
    └── page3-customer.png
```

---

## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `Quoodo new.pbix` in Power BI Desktop
4. Use the slicers/filters on each page to explore the data interactively

---

## 📸 Preview

### Quoodo Dashboard
![Quoodo Dashboard](screenshots/page1-overview.png)

### Product Analysis
![Product Analysis](screenshots/page2-product.png)

### Customer Analysis
![Customer Analysis](screenshots/page3-customer.png)

---

## 📬 Contact

Feel free to open an issue or reach out if you have questions about this dashboard!
