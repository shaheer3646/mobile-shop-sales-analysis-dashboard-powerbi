🧾 Power BI Mobile Shop Sales Dashboard

Interactive dashboard to monitor mobile shop sales performance across regions, categories, and months, enabling data-driven inventory and sales decisions.

---

## 📌 Table of Contents

- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#key-findings">Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>

---

## <a class="anchor" id="overview"></a>Overview

This project tracks and analyzes mobile shop sales using Power BI. The dashboard provides interactive visualizations to monitor sales trends, top products, and regional performance. Data was cleaned and transformed to ensure accuracy and actionable insights.

---

## <a class="anchor" id="business-problem"></a>Business Problem

Mobile retail shops require efficient tracking of sales and inventory. This project focuses on:

- Identifying top-selling and underperforming products
- Monitoring regional and monthly sales trends
- Supporting inventory allocation and purchasing decisions
- Detecting revenue growth opportunities

---

## <a class="anchor" id="dataset"></a>Dataset

- **File:** `data/mobile sales data.xlsx`
- Contains sales transactions including product, category, region, sales quantity, revenue, and purchase cost.
- Data was cleaned and aggregated for accurate reporting.

---

## <a class="anchor" id="tools--technologies"></a>Tools & Technologies

- **Power BI Desktop:** Dashboard development, KPIs, slicers
- **Power Query:** Data cleaning and transformation
- **Python / SQL:** Optional for advanced analysis

---

## <a class="anchor" id="project-structure"></a>Project Structure

```text
vendor-performance-analysis/
│
├── README.md
├── images/
│   ├── average.png
│   ├── filter.png
│   ├── maxicon.png
│   ├── quality.png
│   ├── transactions.png
│   ├── dashboard.jpg
│   ├── Mid report.jpg
│   └── period last year.jpg
├── dashboard/
│   └── Ms_dashboard.pbix
├── data/
│   └── mobile sales data.xlsx
```

---

## <a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation

- Removed duplicates and invalid transactions
- Handled missing sales and revenue values
- Standardized product categories and regions
- Aggregated sales data at product, category, and region levels

---

## <a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)

- Identified underperforming product lines
- Evaluated monthly and regional sales trends
- Checked for negative/zero sales entries
- Visualized revenue trends and top-selling products

---

## <a class="anchor" id="key-findings"></a>Key Findings

- **Top-Selling Products:** 10 products contribute \~60% of total revenue
- **Revenue Trends:** Seasonal peaks in regional sales
- **Underperforming Segments:** Products with consistently low sales
- **Inventory Insights:** Improved stock allocation can reduce unsold inventory by \~15%

---

## <a class="anchor" id="dashboard"></a>Dashboard

- Power BI dashboard provides:

  - Region-wise sales and revenue
  - Product category performance
  - Monthly revenue trends
  - KPIs and slicers for top products




 

**Preview Showcase:**
![Dashboard](https://github.com/shaheer3646/mobile-shop-sales-analysis-dashboard-powerbi/blob/5c4aa229d43402be8a13f1f5035472cbec6ddf88/Images/Dashboard.jpg)


---

## <a class="anchor" id="how-to-run-this-project"></a>How to Run This Project

1. Open the Power BI dashboard file:

```text
dashboard/Ms_dashboard.pbix
```

2. Refresh the data if required in Power BI Desktop.
3. Explore visuals, KPIs, and slicers to analyze sales trends and insights.

---

## <a class="anchor" id="final-recommendations"></a>Final Recommendations

- Focus marketing efforts on underperforming product segments
- Optimize inventory allocation based on top-selling products
- Use KPIs to monitor regional performance continuously
- Strategically plan bulk purchases to maximize revenue
