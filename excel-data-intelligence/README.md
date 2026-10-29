# 📊 Retail Sales Data Intelligence Dashboard & Advanced Analytics

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Analytics](https://img.shields.io/badge/Data_Analytics-Business_Intelligence-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 🎥 Project Demo

Watch the project demonstration to explore the worksheets, formulas, and calculation results.

<div align="center">

🔗 **Project Demo Video:** [▶️ Watch on Google Drive](https://drive.google.com/file/d/15-Y81eJOt8NlLtjtyL0qiNK6vj9jLJBL/view?usp=sharing)

</div>

---

## 📌 Project Overview

This project is a comprehensive **Retail Sales Data Intelligence & Business Analytics Dashboard** built using Microsoft Excel's advanced analytical functions, dynamic modeling, and statistical tools.

The workbook provides a multi-dimensional analysis of **250 retail transactions**, covering customer purchasing patterns, category-wise revenue distribution, regional sales performance, Month-over-Month (MoM) tracking, What-If scenario simulations, and linear regression modeling.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value | Business Insight |
| :--- | :--- | :--- |
| **Total Revenue** | **$229,192.47** | Cumulative sales revenue across all categories |
| **Total Orders** | **250** | Overall transaction volume |
| **Average Order Value (AOV)** | **$916.77** | Average revenue generated per customer transaction |
| **Total Units Sold** | **753 units** | High retail inventory movement |
| **Unique Customers** | **50** | Diverse customer base across multiple segments |
| **Top Category** | **Electronics** | Accounts for **74.94%** of total business revenue |
| **Top Performing Region** | **East** | Contributes **$59,288.39** (~25.87% revenue share) |

---

## 🗂️ Workbook Architecture & Module Breakdown

The workbook is divided into a structured, modular workflow:

### 1. `Dataset` (Raw Data Layer)
* **Description:** Master transactional repository of 250 verified retail sales records.
* **Key Fields:** `Transaction_ID`, `Date`, `Customer_ID`, `Customer_Name`, `Product_ID`, `Product_Name`, `Category`, `Quantity`, `Unit_Price`, `Payment_Method`, `Region`, `Customer_Segment`, `Customer_Since`, `Total_Amount`.

### 2. `Analysis` (Core KPI & Performance Engine)
* **Date & Time Tracking:** Dynamic time calculations using `=TODAY()`, `=NOW()`, `=MIN()`, and `=MAX()` to track the transaction timeline.
* **Category-wise Breakdown:**
  * **Electronics:** $171,756.05 (131 orders | 74.94% share)
  * **Furniture:** $49,097.68 (76 orders | 21.42% share)
  * **Appliances:** $8,338.74 (43 orders | 3.64% share)
* **Regional Distribution:** Performance tracking across the Central, East, North, South, and West regions.
* **Product-Level Breakdown:** Unit sales and revenue metrics for 10 core products (Laptops, Desks, Bookshelves, Monitors, etc.).

### 3. `Conditional_Formatting` (MoM Growth & Trend Analytics)
* **Dynamic Time Series:** Monthly dates generated dynamically using `=DATE()` and `=EDATE()`.
* **Revenue Calculation:** Strict monthly-boundary revenue aggregation using `=SUMIFS()` and `=EOMONTH()`.
* **MoM Variance & Trend Indicators:**
  * Automated percentage growth formula: `=(Current - Previous) / Previous`.
  * Visual status tracking using dynamic logic:
    ```excel
    =IF(Change > 0, "▲ Up", IF(Change < 0, "▼ Down", "▬ Same"))
    ```
  * Soft color heatmaps and direction indicators for executive reporting.

### 4. `Advanced_Analysis` (Predictive Modeling & What-If Simulations)
* **Goal Seek Simulation:** Determined the sales volume required to reach a target revenue of $300,000 and a net profit of $120,000 (at a 40% margin): **985.64 units at an average price of $304.37**.
* **Scenario Manager:** Sensitivity planning model built across three scenarios:
  * **Current Case:** 986 units @ $304.37
  * **Best Case:** 900 units @ $320.00
  * **Worst Case:** 600 units @ $280.00
* **Linear Regression (Data Analysis ToolPak):**
  * Evaluated the relationship between `Quantity` and `Total_Amount`.
  * **Observations:** 250
  * **Multiple R:** 0.458 | **R Square ($R^2$):** 0.2098
  * **F-Significance / P-Value:** $2.26 \times 10^{-14}$ (statistically highly significant relationship).

### 5. `Dashboard` & `Summary` (Executive Reporting Layer)
* High-level executive view with KPI callouts, category share breakdowns, and actionable business recommendations.

---

## 🛠️ Advanced Excel Toolkit & Functions Used

* **Lookup & Reference:** Dynamic ranges and cross-sheet cell references.
* **Logical & Aggregation Functions:** `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `IF`, `MIN`, `MAX`.
* **Date & Time Intelligence:** `TODAY()`, `NOW()`, `DATE()`, `EDATE()`, `EOMONTH()`.
* **Statistical & Predictive Analysis:** Excel Analysis ToolPak (Linear Regression, ANOVA summary output, coefficient significance testing).
* **Decision Support Modeling:** Goal Seek, Scenario Manager.
* **Visualization:** Conditional Formatting rules, Data Bars, Custom Trend Icons, Pivot Tables.

---

## 🖼️ Workbook Module Previews

### 1. Raw Dataset Layer 
The master transactional repository of 250 verified retail sales records, with transaction details, customer profiles, product categories, and payment methods cleanly structured.

![Dataset Preview](Output/Dataset.png)

---

### 2. Core KPI & Data Analysis Engine
Category-wise revenue distribution, product-level unit sales aggregation, regional metrics, and dynamic date calculations (`TODAY()`, `NOW()`, `MIN()`, `MAX()`).

![Data Analysis Preview](Output/Data-analysis.png)

---

### 3. Conditional Formatting & MoM Trends 
Dynamic time-series analysis using `=DATE()`, `=EDATE()`, and `=SUMIFS()` to track monthly sales boundaries. MoM growth status is visualized with automated icons (`▲ Up`, `▼ Down`, `▬ Same`) and color bars.

![Conditional Formatting Preview](Output/Conditional-formating.png)

---

### 4. Advanced What-If & Linear Regression 
Linear Regression output from the Excel Data Analysis ToolPak (Multiple R: 0.458, $R^2$: 0.2098, F-Significance: $2.26 \times 10^{-14}$), along with Goal Seek and Scenario Manager implementations for revenue and profit sensitivity.

![Linear Regression & Modeling](Output/Linear-regression.png)

---

## 💡 Business Findings & Actionable Insights

1. **Electronics Dominance:** Electronics generates ~75% of total revenue, with Laptops and Monitors being the highest-ticket items.
2. **Regional Opportunity:** The East and North regions together generate over 48% of total revenue, while the South region is the lowest contributor ($36.4K), highlighting the need for a targeted marketing campaign.
3. **Seasonal Spikes:** Major revenue surges were observed in October and December (December shows +87.1% MoM growth), indicating strong Q4 festive-season shopping demand.

---

## 🚀 How to Explore the Workbook

1. Clone or download the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the Excel workbook in Microsoft Excel (2016 or later recommended).
3. Review the sheets in order: `Dataset` → `Analysis` → `Conditional_Formatting` → `Advanced_Analysis` → `Dashboard` / `Summary`.
4. Enable the **Analysis ToolPak** add-in (File → Options → Add-ins) if you want to re-run the regression.
5. Check the `Output/` folder for screenshots of each module, or watch the demo video linked above.

---
