# ☕ Coffee Shop Sales Analysis & Interactive Excel Dashboard

## 📊 Project Overview

This project analyzes coffee shop sales data using Microsoft Excel to transform transactional data into actionable business insights.

The analysis covers sales performance, customer behavior, product performance, geographic distribution, coffee types, roast-type classifications, order trends, and loyalty-card activity.

The project combines data preparation, lookup-based data integration, PivotTables, PivotCharts, and dashboard design to create an interactive business analytics solution.

---

## 🎯 Business Objective

The objective of this project was to analyze coffee sales data and answer practical business questions such as:

* Which markets generate the most revenue?
* Which coffee types perform best?
* How does sales performance change over time?
* Which customers contribute the most revenue?
* Which product sizes generate the most sales?
* How are sales distributed across the dataset's roast-type classifications?
* How do loyalty-card customers compare with non-members?

---

## 🗂️ Dataset Overview

The workbook contains **1,000 transaction records** covering the period from **January 2, 2019 to August 19, 2022**.

The dataset contains information related to:

* Orders
* Customers
* Products
* Coffee types
* Roast types
* Product sizes
* Unit prices
* Sales
* Countries
* Loyalty-card status

The dataset contains:

* **1,000 transaction records**
* **957 unique orders**
* **913 unique customers**
* **48 unique products**
* **3,551 units sold**
* **$45,134.26 total recorded sales**

---

## 🛠️ Tools & Techniques

### Microsoft Excel

* Data preparation
* Data integration
* XLOOKUP
* INDEX & MATCH
* IF formulas
* PivotTables
* PivotCharts
* Data aggregation
* Customer segmentation
* Geographic analysis
* Time-series analysis
* Dashboard development
* Data visualization

---

## 📈 Key Findings

### 🌎 Sales by Country
<img width="1343" height="598" alt="sales-analysis" src="https://github.com/user-attachments/assets/70d335fc-092c-44a3-b2de-763581d702d5" />


The United States was the dominant market, generating **$35,638.89**, approximately **79% of total recorded sales**.

| Country        |      Sales |
| -------------- | ---------: |
| United States  | $35,638.89 |
| Ireland        |  $6,696.87 |
| United Kingdom |  $2,798.51 |

This indicates that the United States was the primary revenue-generating market in the analyzed dataset.

---

### ☕ Sales by Coffee Type

Excelsa generated the highest sales among the four coffee types, with **$12,306.44** in recorded sales.

| Coffee Type |      Sales |
| ----------- | ---------: |
| Excelsa     | $12,306.44 |
| Liberica    | $12,054.08 |
| Arabica     | $11,768.50 |
| Robusta     |  $9,005.25 |

The relatively close performance of Excelsa, Liberica, and Arabica indicates that sales were distributed across several coffee categories rather than being concentrated entirely in one type.

---

### 🔥 Roast Type Analysis

The dataset's `Roast Type Name` field contains the classifications **Large, Medium, and Dark**.

| Roast Type Name |      Sales |
| --------------- | ---------: |
| Large           | $17,354.47 |
| Medium          | $14,600.48 |
| Dark            | $13,179.32 |

**Note:** These classifications are reported exactly as provided in the source dataset.

---

### 📦 Sales by Product Size

The 2.5 size category generated the highest recorded sales.

| Size |      Sales |
| ---: | ---------: |
|  2.5 | $23,785.57 |
|  1.0 | $11,010.75 |
|  0.5 |  $7,029.99 |
|  0.2 |  $3,307.95 |

The 2.5 size category accounted for more than half of total recorded sales.

---

### 📅 Annual Sales

| Year  |      Sales |
| ----- | ---------: |
| 2019  | $12,187.17 |
| 2020  | $12,117.55 |
| 2021  | $13,766.11 |
| 2022* |  $7,063.44 |

*2022 is a partial year, with data available through August 19, 2022, so it should not be directly compared with the full-year totals for 2019–2021.

The highest full-year sales total occurred in **2021**, reaching approximately **$13.77K**.

---

### 👥 Top 5 Customers
<img width="938" height="394" alt="customer-analysis" src="https://github.com/user-attachments/assets/672dba6a-8fd3-4bc5-846f-e581f1f3280a" />


The analysis identifies the highest-value customers based on recorded sales.

| Customer        |   Sales |
| --------------- | ------: |
| Allis Wilmore   | $317.07 |
| Brenn Dundredge | $307.05 |
| Terri Farra     | $289.11 |
| Nealson Cuttler | $281.67 |
| Don Flintiff    | $278.01 |

This analysis demonstrates how customer-level sales data can be used to identify high-value customers and support future retention or loyalty strategies.

---

### 🎫 Loyalty Card Analysis

| Loyalty Card |      Sales |
| ------------ | ---------: |
| No           | $24,216.41 |
| Yes          | $20,917.85 |

In this dataset, customers without a loyalty card generated more total recorded sales than customers with a loyalty card.

This is an observational finding rather than evidence that loyalty programs reduce sales, as other factors may influence the relationship.

---

## 📊 Dashboard
<img width="1204" height="593" alt="dashboard" src="https://github.com/user-attachments/assets/1451d273-2d93-49e1-88f7-2ca746d46181" />


The final Excel dashboard consolidates the analysis into an interactive visual interface.

The dashboard enables users to explore:

* Overall sales performance
* Sales trends
* Country-level performance
* Coffee-type performance
* Customer performance
* Product characteristics
* Other transaction-level dimensions

The supporting worksheets provide the underlying analysis used to build the dashboard.

---

## 💡 Business Insights

The analysis highlights several important patterns:

1. **The United States is the primary revenue market**, contributing approximately 79% of total recorded sales.

2. **Excelsa is the highest-selling coffee type**, although Liberica and Arabica are relatively close in total sales.

3. **The 2.5 size category generates the largest share of sales**, accounting for more than half of total recorded revenue.

4. **2021 was the strongest complete year** in the dataset, with approximately $13.77K in recorded sales.

5. **Sales are relatively diversified across the major coffee types**, reducing dependence on a single coffee category.

6. **Customer-level analysis identifies high-value customers**, providing opportunities for targeted retention and loyalty strategies.

---

## 📌 Business Value

This project demonstrates how Microsoft Excel can be used as a practical business analytics tool to move from raw transactional data to decision-ready insights.

The analysis could support decisions related to:

* Market prioritization
* Product and size performance
* Customer retention
* Sales monitoring
* Product mix
* Geographic strategy
* Loyalty-program analysis

---

## 📚 Skills Demonstrated

### Data Analytics

Data preparation · Data integration · Exploratory analysis · Aggregation · Business insights

### Microsoft Excel

XLOOKUP · INDEX & MATCH · IF formulas · PivotTables · PivotCharts · Dashboarding · Data visualization

### Business Analytics

Sales analysis · Customer analysis · Product analysis · Geographic analysis · Trend analysis · Segmentation

---

## 📁 Workbook Structure

The project workbook contains the following analytical components:

* `Dashboard` — Interactive dashboard
* `Top 5 Customers` — Highest-value customer analysis
* `Country Barchart` — Geographic sales comparison
* `Total sales` — Time-based sales analysis by coffee type
* `orders` — Transaction-level dataset and calculated fields
* `customers` — Customer information
* `products` — Product information

---

## 🚀 Project Outcome

The project transformed **1,000 coffee sales transactions** into a structured Excel analytics solution containing data integration, analytical worksheets, visualizations, and an interactive dashboard.

It demonstrates the ability to use Excel not only for spreadsheet management, but also for **data preparation, analysis, visualization, and business decision support**.
