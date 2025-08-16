# 📊 Google Sheets Project: KPI-based Sales Analysis

This project analyzes sales data to track **Key Performance Indicators (KPIs)** such as:
- Customer sales performance
- Product & category performance
- ARPU (Average Revenue Per User) by state
- City-level category breakdowns
- Festival period sales performance

## 🔹 Project Tasks

### Task 1: Customer & Transaction Analysis
- Calculated sales per transaction (`Sales = Quantity × Price`).
- Aggregated total bill per `customer_id` + `transaction_id`.
- ✅ Found top customer by sales.

### Task 2: Festival Period Sales (8th–15th Dec)
- Filtered data for festival offer period.
- Used `SUMIFS` to calculate product-wise sales.
- Applied `VLOOKUP` to map product descriptions.
- ✅ Identified top-selling product and sales amount.

### Task 3: ARPU (Average Revenue per User)
- Mapped states via `VLOOKUP` from `geography_dim`.
- Computed total sales & unique customers per state.
- ✅ Calculated ARPU for Maharashtra and other states.

### Task 4: Sales by Category & City
- Mapped categories via `VLOOKUP`.
- Used `SUMIFS` to compute category × city sales.
- ✅ Found which city contributed the most to each category.

---

## 🔹 Tools & Skills Applied
- Excel formulas: `SUMIFS`, `COUNTIF`, `VLOOKUP`, `IFS`
- Data cleaning & duplicate removal
- Pivoting and filtering for KPI reports
- Report formatting (tables, conditional formatting, filters)
- Exporting results into PDF dashboards

---

## 🔹 Sample Insights
- **Top Customer**: [XYZ_ID] had the highest sales.
- **Festival Offer**: [Product X] drove the highest revenue.
- **Maharashtra ARPU**: ₹[amount].
- **Category Performance**: ‘Cereals’ sold highest in Pune.

---

## 📂 Files
- **Excel Workbook**: Contains all data cleaning & analysis steps.
- **PDF Report**: Summary for quick review (formatted for managers).
- **Sample Datasets**: For reproducibility (anonymized).

---

## 📌 Learning Outcome
This project demonstrates **end-to-end Excel reporting** for business KPIs, combining:
- Raw data transformation  
- KPI calculation  
- Reporting dashboards  

---

#Excel #DataAnalytics #BusinessIntelligence #SalesPerformance #KPIs #ExcelFormulas
