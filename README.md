<div align="center">

# ☕ Coffee Sales Analysis Dashboard

### *Transforming raw sales data into strategic business intelligence using Microsoft Excel*

<br>

![Dashboard Preview](https://github.com/AmanManiTiwari/Coffee-Sales-Dashboard-/raw/main/Dashboard.png)

<br>

[![Excel](https://img.shields.io/badge/Built%20with-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](https://github.com/AmanManiTiwari/Coffee-Sales-Dashboard-)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Portfolio](https://img.shields.io/badge/Type-Portfolio%20Project-orange?style=for-the-badge)](https://github.com/AmanManiTiwari)

</div>

---

## 📌 Overview

This project delivers a fully interactive **Coffee Sales Analysis Dashboard** built in Microsoft Excel — no external BI tools required. It transforms raw transactional order data into a clean, executive-level view of business performance across time, geography, and product segments.

The goal was to answer a single question: *"What does the data tell us about where coffee sales are growing, stalling, or thriving?"*

---

## 🎯 Business Questions Answered

| # | Question | Answer Found In |
|---|----------|----------------|
| 1 | Which country drives the most revenue? | Country Sales Bar Chart |
| 2 | Which coffee type sells best? | Product Type Breakdown |
| 3 | Are there seasonal sales patterns? | Monthly Trend Line Chart |
| 4 | Who are our top customers? | Top 5 Customers Chart |
| 5 | How does loyalty card status affect purchasing? | Loyalty Slicer Filter |

---

## 📊 Dashboard Features

```
┌─────────────────────────────────────────────────────────────────┐
│  INTERACTIVE FILTERS          │  KEY METRICS                    │
│  ─────────────────────────    │  ───────────────────────────    │
│  ☑ Order Year                 │  📈 Total Sales Over Time       │
│  ☑ Roast Type                 │  🌍 Sales by Country            │
│  ☑ Coffee Size                │  👑 Top 5 Customers             │
│  ☑ Loyalty Card               │                                 │
└─────────────────────────────────────────────────────────────────┘
```

- **Dynamic Slicers** — filter by year, roast type, pack size, and loyalty card status simultaneously
- **Time Series Analysis** — visualize revenue trends across months and years per coffee type
- **Geographic Breakdown** — compare sales performance across USA, UK, and Ireland
- **Customer Segmentation** — identify and rank top revenue-generating customers
- **Pivot-Powered Charts** — all visuals update instantly when filters change

---

## 🔍 Key Insights

> **USA dominates** — the United States accounts for the largest share of total coffee sales by a significant margin.

> **Arabica leads in volume** — among all four coffee types (Arabica, Excelsa, Liberica, Robusta), Arabica consistently tops sales figures.

> **Seasonal spikes exist** — sales exhibit a noticeable seasonal rhythm, peaking during specific months — signaling opportunities for targeted promotions.

> **Loyalty card holders matter** — filtering by loyalty card status reveals distinct purchasing patterns that can inform retention strategy.

---

## 🗂️ Repository Structure

```
Coffee-Sales-Dashboard-/
│
├── 📊 coffeeOrdersProject.xlsx   ← Main file: dashboard + analysis
├── 📋 coffeeOrdersData.xlsx      ← Raw source data (orders, customers, products)
├── 🖼️  Dashboard.png              ← Dashboard screenshot preview
└── 📄 README.md                  ← You are here
```

---

## 🛠️ Technical Stack

| Tool | Usage |
|------|-------|
| **Microsoft Excel** | Primary platform for data analysis and visualization |
| **Pivot Tables** | Data aggregation and summarization engine |
| **Pivot Charts** | Dynamic visual output tied to slicers |
| **XLOOKUP / INDEX-MATCH** | Cross-table data enrichment |
| **Slicers & Timelines** | Interactive filtering layer |
| **Data Cleaning** | Duplicate removal, formatting standardization |

---

## 🚀 Getting Started

**Prerequisites:** Microsoft Excel 2016 or later (for full slicer and pivot functionality)

```bash
# 1. Clone the repository
git clone https://github.com/AmanManiTiwari/Coffee-Sales-Dashboard-.git

# 2. Open the main project file
open coffeeOrdersProject.xlsx
```

**Using the Dashboard:**
1. Open `coffeeOrdersProject.xlsx` and navigate to the **Dashboard** sheet
2. Use the **slicers** (Order Year, Roast Type, Size, Loyalty Card) to filter the view
3. All charts update automatically — no manual refresh needed
4. To explore raw data, check the **Orders**, **Customers**, and **Products** sheets

---

## 📈 Data Pipeline

```
Raw Data (coffeeOrdersData.xlsx)
        │
        ▼
  Data Cleaning & Enrichment
  (XLOOKUP to join customer & product info)
        │
        ▼
  Pivot Tables (aggregation)
        │
        ▼
  Pivot Charts + Slicers (interactivity)
        │
        ▼
  Final Dashboard (coffeeOrdersProject.xlsx)
```

---

## 💡 Skills Demonstrated

- **Data Wrangling** — merging and cleaning multi-table datasets in Excel
- **Analytical Thinking** — translating business questions into dashboard metrics
- **Data Visualization** — choosing the right chart type for each insight
- **Dashboard UX** — designing for non-technical stakeholders with clean, intuitive layouts
- **Excel Proficiency** — advanced functions (XLOOKUP), Pivot Tables, Slicers, and chart formatting

---

## 🙋 About the Author

**Aman Mani Tiwari** — Data Analyst focused on turning messy datasets into clear business narratives.

[![GitHub](https://img.shields.io/badge/GitHub-AmanManiTiwari-181717?style=flat-square&logo=github)](https://github.com/AmanManiTiwari)

---

<div align="center">

*If this project was useful, consider giving it a ⭐ — it helps others discover it!*

</div>
