<!-- ======================= HEADER WAVE ======================= -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=140&section=header&text=Customer%20Sales%20Analyzer&fontSize=30&fontColor=ffffff&fontAlignY=38&desc=Excel-Based%20Sales%20Analytics%20Project&descSize=15&descAlignY=58&animation=fadeIn" alt="Customer Sales Analyzer Header"/>

<div align="center">

![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Sales%20Analytics-2563EB?style=for-the-badge)
![Records](https://img.shields.io/badge/Records-200-F59E0B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-16A34A?style=for-the-badge)

</div>

---

## 🎥 Project Demo

Watch the project demonstration to explore the worksheets, formulas, and calculation results.

<div align="center">

🔗 **Project Demo Video:** [▶️ Watch on Google Drive](https://drive.google.com/file/d/1JrXgdcClMDSiAFp-ZE5X0IylzzesXmxQ/view?usp=sharing)

</div>

---

## 📊 Customer Sales Analyzer

An Excel-based sales analytics project that transforms customer
transaction data into useful business insights using Excel formulas,
customer analysis, What-If Analysis, statistical analysis, PivotTables,
and dashboard visualizations.

---

## 🔎 Project Overview

**Customer Sales Analyzer** is a practical Microsoft Excel project
focused on understanding sales performance and customer purchasing
patterns. The workbook uses formulas, lookup functions, statistical
tools, and summary tables to analyze transactions, compare regions and
product categories, explore discount scenarios, and review monthly sales
trends. The results are presented through a dashboard to make the
analysis easier to understand.

## 🎯 Project Objectives

- 📌 Summarize sales, profit, and profit margin.
- 👥 Identify customers with high total purchases.
- 🌍 Compare sales performance across regions and product categories.
- 🏷️ Explore discount scenarios using What-If Analysis.
- 📉 Examine the relationship between sales and profit through regression.
- 📅 Analyze monthly sales trends and present key metrics in a dashboard.

---

## 🗂️ Dataset

The `Dataset` worksheet contains **200 transaction records**.

| Column | Description |
|---|---|
| `Customer_ID` | Customer identifier |
| `Customer_Name` | Customer name |
| `Region` | Sales region |
| `Product_Category` | Product category |
| `Sales` | Sales amount for a transaction |
| `Quantity` | Number of units sold |
| `Discount` | Discount rate |
| `Order_Date` | Transaction date |
| `Profit` | Profit for a transaction |

## 📂 Workbook Structure

| Worksheet | Description |
|---|---|
| `Dataset` | Source transaction records used for the analysis |
| `Analysis` | Customer purchase analysis, discount scenarios, regression, descriptive statistics, monthly sales growth, and high-value customer analysis |
| `Dashboard` | KPI summaries, PivotTable analysis, and charts |
| `Dashboard Summary` | Written summary of the main findings |

---

## ✅ Analysis Performed

1. **Customer Sales Analysis:** Calculates total purchases by customer and supports customer ranking.
2. **Discount What-If Analysis:** Compares profit estimates under different discount scenarios.
3. **Regression Analysis:** Examines the relationship between sales and profit using Excel's Data Analysis ToolPak.
4. **Descriptive Statistics:** Summarizes selected data using measures such as mean, median, standard deviation, minimum, and maximum.
5. **Monthly Sales Trends:** Calculates monthly sales and month-over-month growth.
6. **Timestamp:** Uses `NOW()` to show the workbook's recalculation date and time.
7. **High-Value Customers:** Filters customers whose total purchases exceed 8,000.
8. **Regional and Category Analysis:** Uses a PivotTable to summarize sales by region and product category.
9. **Dashboard Visualization:** Presents key metrics through KPI summaries and bar, line, and pie charts.

## 🛠️ Excel Functions and Features

**Formulas and Functions**

| Purpose | Functions |
|---|---|
| Aggregation | `SUM`, `AVERAGE`, `MEDIAN`, `MIN`, `MAX`, `COUNT` |
| Logical and error handling | `IF`, `IFERROR` |
| Conditional aggregation | `SUMIF`, `SUMIFS` |
| Lookup and matching | `VLOOKUP`, `INDEX`, `MATCH` |
| Dynamic arrays | `UNIQUE`, `FILTER` |
| Date and time | `EDATE`, `NOW` |

**Analysis Features**

- 🎨 Conditional Formatting
- 🔮 What-If Analysis
- 📐 Regression and Descriptive Statistics using the Data Analysis ToolPak
- 🧮 PivotTables
- 📊 KPI summaries and charts
- 🔢 Custom number formatting for growth indicators

---
## 🧮 Key Formulas Used

| Purpose | Formula |
|---|---|
| Total Sales | `=SUM(Dataset!E2:E201)` |
| Total Profit | `=SUM(Dataset!I2:I201)` |
| Profit Margin | `=SUM(Dataset!I2:I201)/SUM(Dataset!E2:E201)` |
| Customer Total Purchase | `=SUMIF(Dataset!A2:A201, A2, Dataset!E2:E201)` |
| Region-wise Sales | `=SUMIFS(Dataset!E:E, Dataset!C:C, "West")` |
| Customer Lookup | `=IFERROR(INDEX(Dataset!B:B, MATCH(A2, Dataset!A:A, 0)), "Not Found")` |
| High-Value Customers | `=FILTER(A2:B30, B2:B30>8000)` |
| Month-over-Month Growth | `=(C3-C2)/C2` |

## 📈 Key Results

The workbook's current summary reports the following figures:

| Metric | Result |
|---|---:|
| 💰 Total Sales | 195,217.76 |
| 📈 Total Profit | 68,287.01 |
| 🎯 Profit Margin | ≈ 35.0% |
| 🧾 Transaction Records | 200 |
| 🛍️ Product Categories | 5 |
| 🌍 Sales Regions | 5 |

## 💡 Key Business Insights

- **Top region:** West leads with about 44,084 in sales, followed by Central (≈ 43,468) and South (≈ 40,249). East is the lowest (≈ 32,442).
- **Top category:** Books generate the highest sales (≈ 47,002), while Office Supplies are the weakest (≈ 28,631).
- **Sales vs. profit:** Regression gives Profit ≈ 0.351 × Sales − 1.03 with R² ≈ 0.60, so sales explain about 60% of the variation in profit. The relationship is statistically significant (p < 0.001).
- **High-value customers:** Several customers exceed 8,000 in total purchases, with CUST015 (≈ 11,611) and CUST028 (≈ 10,294) among the highest.
- **Discount impact:** The What-If analysis compares profit under discount rates from 0% to 20%.
- **Trend analysis:** Monthly sales and month-over-month growth are tracked and shown with up/down indicators.

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:134E2A,50:217346,100:3FA66B&height=110&section=header&text=Output%20Screenshots&fontSize=36&fontColor=ffffff&fontAlignY=32" alt="Output Screenshots"/>

## 🖼️ Output Screenshots

### 1. Executive Dashboard & Visualizations
![Dashboard Overview](Output/dashboard-overview.png)

### 2. Monthly Revenue Trend & Seasonality
![Monthly Sales Trend](Output/dashboard-overview1.png)

### 3. Statistical Regression & What-If Sensitivity Analysis
![Statistical Analysis](Output/statistical-modeling.png)

### 4. Customer Lookup & High-Value Segmentation
![Customer Analytics](Output/customer-lookup-trends.png)

### 5. Project Executive Summary
![Dashboard Summary](Output/project-summary-card.png)

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Review the `Dataset`, `Analysis`, and `Dashboard` worksheets.
4. Select calculated cells to inspect their formulas in the formula bar.
5. Check that formula-driven outputs have recalculated correctly.

## 📁 Repository Structure

```text
PR2-Customer-Sales-Analyzer/
│
├── README.md
├── PR2-Customer_Sales_Analyzers.xlsx
└── Output/
    ├── dashboard-overview.png
    ├── dashboard-overview1.png
    ├── statistical-modeling.png
    ├── customer-lookup-trends.png
    └── project-summary-card.png
```

## 🔮 Future Improvements

- Add interactive slicers and filters for regions, categories, and dates.
- Create additional charts for monthly sales and profitability.
- Improve formatting with consistent colors, number formats, and conditional formatting.
- Validate formulas and refresh dashboard outputs when the source data changes.
- Add business recommendations based on the analysis results.

---

## ✅ Conclusion

The **Customer Sales Analyzer** project shows how Microsoft Excel can be used to turn raw transaction data into clear, decision-ready insights.

- The dataset of 200 transactions generated **195,217.76 in sales** and **68,287.01 in profit**, a profit margin of about **35%**.
- **West** is the strongest region and **Books** is the strongest product category, while **Office Supplies** has the lowest sales.
- Regression analysis shows a **strong, statistically significant link between sales and profit** (R² ≈ 0.60).
- Customer analysis identifies **high-value customers** who contribute a large share of total purchases and are worth prioritising.
- What-If Analysis helps estimate how different discount levels can affect overall profit.
- The dashboard brings these results together through KPIs and charts, so performance can be understood at a glance.

Overall, the project demonstrates practical skills in formulas, lookup functions, statistical analysis, PivotTables, and data visualization.

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:134E2A,50:217346,100:3FA66B&height=120&section=footer&text=Thank%20You&fontSize=30&fontColor=ffffff&fontAlignY=65" alt="Thank You"/>
