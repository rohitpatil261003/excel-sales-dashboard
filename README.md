<h1>Excel Dashboard Project</h1>
<ul>
  <li>This Dashboard Shows Sales Analysis using Excel.</li>
  <li>Tools: Excel, Pivot Tables, Charts</li>
</ul>
<img src="Sale_Dashboard.png"/>

# 📊 Interactive Sales Performance Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel Badge" />
  <img src="https://img.shields.io/badge/Focus-Sales%20%26%20Revenue%20Analytics-blue?style=for-the-badge" alt="Focus Badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status Badge" />
</p>

---

## 📌 Table of Contents
* [Overview](#-overview)
* [Key Metrics (KPIs)](#-key-metrics-kpis)
* [Dashboard Preview](#-dashboard-preview)
* [Core Features & Interactive Elements](#-core-features--interactive-elements)
* [Data Architecture & Formulas](#-data-architecture--formulas)
* [How to Use & Download](#-how-to-use--download)
* [Future Enhancements](#-future-enhancements)

---

## 🔎 Overview
This project delivers an interactive executive sales dashboard built with Microsoft Excel to track and optimize business revenue, profitability, and sales targets across key product lines.

> [!NOTE]
> Designed for quick executive decision-making using dynamic slicers, time-series variance analysis, and multi-dimensional pivot tables.

---

## 📈 Key Metrics (KPIs)

| Metric | Recorded Value | Budget Comparison |
| :--- | :---: | :---: |
| **Total Revenue** | ₹21,39,83,614 | `+1.8%` vs Budget |
| **Total Profit** | ₹5,64,29,310 | `-6.6%` vs Budget |
| **Profit Margin (%)** | 26.37% | `-8.3%` vs Target |
| **Total Units Sold** | 13,50,956 | `-4.9%` vs Target |

---

## 🖥️ Dashboard Preview

<p align="center">
  <img src="Sale_Dashboard.png" alt="Sales Dashboard Preview" width="950" />
</p>

---

## ⚡ Core Features & Interactive Elements

* **Dynamic Timeline & Slicers:** Filter instantly by Year, Quarter, and Month to view period-specific performance.
* **Target Variance Tracking:** Visual comparison of Total Revenue vs. Actuals across budget checkpoints.
* **Product Profit Breakdown:** Donut visual segmenting contributions across top products (City Cruiser, Road Racer, Trail Master, etc.).
* **Dynamic Cards:** Formatted KPI cards highlighting percentage deviations against predefined targets.

---

## 🗂️ Data Architecture & Formulas

<details>
<summary><b>Click to expand Pivot Tables & Calculation details</b></summary>

<br>

### 1. Calculated KPI Fields
* **Profit Margin (%):**
  $$\text{Profit Margin} = \frac{\text{Total Profit}}{\text{Total Revenue}} \times 100$$
* **Variance vs. Budget:**
  $$\text{Variance \%} = \frac{\text{Actual Metric} - \text{Budgeted Metric}}{\text{Budgeted Metric}} \times 100$$

### 2. Excel Components Used
* **Pivot Tables:** Summarizing revenue by product tier and transaction periods.
* **Pivot Charts:** Combination line charts (Budget vs. Actual) and styled donut distributions.
* **Slicers:** Multi-select timeline and product filters connected across all sheet pivots.

</details>

---

## 🚀 How to Use & Download

1. **Download the Workbook:**  
   [📥 Download `Sales_Data_Set ROHIT.xlsx`](Sales_Data_Set%20ROHIT.xlsx) directly from this repository.
2. **Open in Microsoft Excel:**  
   Open the file in **Excel 2016 or newer** (or Excel for the Web) to ensure full slicer compatibility.
3. **Interact with the Dashboard:**  
   Use the left-hand slicers (Year, Month, Quarter) to filter all summary KPIs and trend charts simultaneously.

---

## 🗺️️ Roadmap & Enhancements

- [x] Initial Excel Pivot Table model & visual layout
- [x] Slicer integration for time-based exploration
- [ ] Add regional/geographic sales breakdown
- [ ] Migrate data model into Power BI / DAX for automated refresh

---

*Authored by [Rohit Bhatu Patil](https://github.com/rohitpatil261003)*
