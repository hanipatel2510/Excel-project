## 🎥 Project Demo

Watch the project demonstration to explore the worksheets, formulas, and calculation results.

🔗 **Project Demo Video:** [Watch on Google Drive](https://drive.google.com/file/d/1JrXgdcClMDSiAFp-ZE5X0IylzzesXmxQ/view?usp=sharing)

## 📊 Customer Sales Analyzer

An Excel-based sales analytics project that transforms customer
transaction data into useful business insights using Excel formulas,
customer analysis, What-If Analysis, statistical analysis, PivotTables,
and dashboard visualizations.

![Tool](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Sales%20Analytics-blue)
![Records](https://img.shields.io/badge/Records-200-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

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

-   Summarize sales, profit, and profit margin.
-   Identify customers with high total purchases.
-   Compare sales performance across regions and product categories.
-   Explore discount scenarios using What-If Analysis.
-   Examine the relationship between sales and profit through
    regression.
-   Analyze monthly sales trends and present key metrics in a dashboard.


## 🗂️ Dataset

The `Dataset` worksheet contains **200 transaction records**.

  Column               Description
  -------------------- --------------------------------
  `Customer_ID`        Customer identifier
  `Customer_Name`      Customer name
  `Region`             Sales region
  `Product_Category`   Product category
  `Sales`              Sales amount for a transaction
  `Quantity`           Number of units sold
  `Discount`           Discount rate
  `Order_Date`         Transaction date
  `Profit`             Profit for a transaction

## 📂 Workbook Structure

  -----------------------------------------------------------------------
  Worksheet                           Description
  ----------------------------------- -----------------------------------
  `Dataset`                           Source transaction records used for
                                      the analysis

  `Analysis`                          Customer purchase analysis,
                                      discount scenarios, regression,
                                      descriptive statistics, monthly
                                      sales growth, and high-value
                                      customer analysis

  `Dashboard`                         KPI summaries, PivotTable analysis,
                                      and charts

  `Dashboard Summary`                 Written summary of the main
                                      findings
  -----------------------------------------------------------------------

## ✅ Analysis Performed

1.  **Customer Sales Analysis:** Calculates total purchases by customer
    and supports customer ranking.
2.  **Discount What-If Analysis:** Compares profit estimates under
    different discount scenarios.
3.  **Regression Analysis:** Examines the relationship between sales and
    profit using Excel's Data Analysis ToolPak.
4.  **Descriptive Statistics:** Summarizes selected data using measures
    such as mean, median, standard deviation, minimum, and maximum.
5.  **Monthly Sales Trends:** Calculates monthly sales and
    month-over-month growth.
6.  **Timestamp:** Uses `NOW()` to show the workbook's recalculation
    date and time.
7.  **High-Value Customers:** Filters customers whose total purchases
    exceed 8,000.
8.  **Regional and Category Analysis:** Uses a PivotTable to summarize
    sales by region and product category.
9.  **Dashboard Visualization:** Presents key metrics through KPI
    summaries and bar, line, and pie charts.

## 🛠️ Excel Functions and Features

**Formulas and Functions**

-   **Aggregation:** `SUM`, `AVERAGE`, `MEDIAN`, `MIN`, `MAX`, `COUNT`
-   **Logical and error handling:** `IF`, `IFERROR`
-   **Conditional aggregation:** `SUMIF`, `SUMIFS`
-   **Lookup and matching:** `VLOOKUP`, `INDEX`, `MATCH`
-   **Dynamic arrays:** `UNIQUE`, `FILTER`
-   **Date and time:** `EDATE`, `NOW`

**Analysis Features**

-   Conditional Formatting
-   What-If Analysis
-   Regression and Descriptive Statistics using the Data Analysis
    ToolPak
-   PivotTables
-   KPI summaries and charts
-   Custom number formatting for growth indicators

## 📈 Key Results

The workbook's current summary reports the following figures:

  Metric                      Result
  --------------------- ------------
  Total Sales             195,217.76
  Total Profit             68,287.01
  Transaction Records            200
  Product Categories               5
  Sales Regions                    5

The workbook also supports comparisons across regions and product
categories, customer purchase segmentation, discount scenarios, and
monthly sales trends.

*These figures describe the workbook version used to prepare this
README. Recheck the summary cells if the dataset or formulas are
changed.*

## 🚀 How to Use

1.  Download or clone this repository.
2.  Open `PR2-Customer_Sales_Analyzers.xlsx` in Microsoft Excel.
3.  Review the `Dataset`, `Analysis`, and `Dashboard` worksheets.
4.  Select formula cells to inspect their formulas in Excel's formula
    bar.
5.  If you change the source data, check the formula ranges and refresh
    the PivotTables.
6.  To rerun regression or descriptive statistics, enable the **Analysis
    ToolPak** add-in in Excel.

## ⚠️ Data Notes

-   The customer ID and customer name mapping should be checked if an ID
    appears with more than one name; lookup formulas such as `VLOOKUP`
    return the first matching record.
-   Some formulas use fixed row ranges. Extend those ranges if
    additional transaction records are added.
-   `NOW()` is a volatile function and updates when Excel recalculates
    the workbook.
-   Check that KPI formulas use consistent data ranges, especially when
    new rows are added.
-   Dynamic-array functions such as `UNIQUE` and `FILTER` require a
    compatible Excel version. Function availability may differ in other
    spreadsheet applications.

---

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
├── PR2-Customer_Sales_Analyzer.xlsx
└── Output/
    ├── dashboard-overview.png
    ├── dashboard-overview1.png
    ├── statistical-modeling.png
    ├── customer-lookup-trends.png
    └── project-summary-card.png
```
## 💡 Key Business Insights

- Analyzed overall sales and profit performance using summary metrics.
- Compared sales performance across regions and product categories.
- Examined customer purchasing patterns to identify high-value customers.
- Explored the potential impact of different discount scenarios on profit.
- Reviewed monthly sales trends to understand changes in performance.


## 🔮 Future Improvements

- Add interactive slicers and filters for regions, categories, and dates.
- Create additional charts for monthly sales and profitability.
- Improve formatting with consistent colors, number formats, and conditional formatting.
- Validate formulas and refresh dashboard outputs when the source data changes.
- Add business recommendations based on the analysis results.

---
