# Executive Summary: Laptop Market Analysis Dashboard

## 📊 Overview

This repository contains an **Executive Summary Dashboard** designed to analyze the laptop and computer market. Built using **Microsoft Power BI**, this dashboard provides a high-level view of product inventory, pricing strategies, revenue generation, and market segmentation by company and product type.

The dashboard allows stakeholders to filter data by price range and specific companies to gain granular insights into market performance.

---

## 🖼️ Dashboard Preview

![Electronics.jpg](https://github.com/ShireenTalaat/Laptop-Market-Analysis-Dashboard/blob/main/Electronics.jpg)

---

## 📈 Key Performance Indicators (KPIs)

The dashboard tracks the following core metrics:

| Metric | Value |
| :--- | :--- |
| **Total Product Count** | 1,273 |
| **Premium Count** | 297 |
| **Budget Count** | 281 |
| **Total Revenue** | 76.32 Million |
| **Max Price** | 324.95K |
| **Min Price** | 9.27K |
| **Average Price** | 59.96K |
| **Price per Inch** | 3.96K |

---

##  Visualizations & Analysis

### 1. Price Distribution by Company
A bar chart illustrating the price distribution across major tech manufacturers.
*   **Top Performer (Highest Price Point):** **Razer** leads significantly, followed by **LG** and **MSI**.
*   **Other Key Players:** Google, Microsoft, Apple, Huawei, Samsung, Toshiba, Dell, Xiaomi, Asus, Lenovo, HP, Fujitsu, Acer, Chuwi, Mediacom, and Vero.

### 2. Product Type Distribution
A pie chart breaking down the inventory by laptop category.
*   **Notebooks:** The dominant category, making up **55.77%** (710 units) of the total inventory.
*   **Gaming Laptops:** The second largest segment at **15.95%** (203 units).
*   **Ultrabooks:** Account for **15%** (191 units).
*   **2 in 1 Convertibles:** **9.11%** (116 units).
*   **Workstations:** **2.28%** (29 units).
*   **Netbooks:** The smallest segment at **1.89%** (24 units).

---

## ️ Interactive Filters

The dashboard includes a sidebar for dynamic filtering:
*   **Price Slider:** Allows users to filter products within a specific price range (Default: 9,270.72 – 324,954.72).
*   **Company Slicer:** A checklist to filter data by specific manufacturers (Acer, Apple, Asus, Dell, HP, Lenovo, Microsoft, etc.).

---

## 🛠️ Tools & Technologies

*   **Microsoft Power BI:** For data visualization and dashboard creation.
*   **DAX (Data Analysis Expressions):** Used for calculating KPIs like Total Revenue and Average Price.
*   **Power Query:** For data cleaning and transformation.

---

## 📁 Project Structure

```text
laptop-market-dashboard/
├── Electronics.jpg          # Screenshot of the dashboard
├── data/
│   └── electronics Price.csv & Electronics_modified.xlsx       # Source dataset 
├── reports/
│   └── executive_summary.pbix # Power BI source file
└── README.md              # This file
```

---

