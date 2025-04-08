# 🚲 Bike Buyers – Data Cleaning & Visualization (Excel Project)

This project showcases how **Microsoft Excel** can be used for complete **data cleaning**, **categorical transformation**, and **dashboard-based visualization**. The dataset contains demographic, socioeconomic, and behavioral data of individuals to determine their likelihood of buying a bike.

---

## 🎯 Project Objectives

- Clean and transform raw customer data into analysis-ready format
- Generate insights on purchasing behavior based on demographic features
- Create an interactive dashboard to visualize key patterns and trends
- Demonstrate Excel-based data analytics workflow without coding

---

## 📁 Dataset Structure

The original dataset (in `bike_buyers` sheet) includes:

| Column Name         | Description |
|---------------------|-------------|
| `ID`                | Unique identifier for each customer |
| `Marital Status`    | Marital status (coded: M/S) |
| `Gender`            | Gender (coded: M/F) |
| `Income`            | Annual income (USD) |
| `Children`          | Number of children |
| `Education`         | Highest education level |
| `Occupation`        | Job type |
| `Home Owner`        | Yes/No for owning a home |
| `Cars`              | Number of cars owned |
| `Commute Distance`  | Distance from home to workplace |
| `Region`            | Customer’s geographic region |
| `Age`               | Age of the customer |
| `Purchased Bike`    | Target variable: Yes or No |

---

## 🧹 Data Cleaning & Transformation (Done in `Working Sheet`)

### ✨ Categorical Fixes
- Replaced short codes (`M`, `F`, `S`) with readable labels:  
  - `M` → `Married`, `F` → `Female`, `S` → `Single`
- Applied `PROPER()` and `TRIM()` functions for uniform casing and spacing

### 🧒 Age Binning
Created a new column `Age-Brackets` with:
- `Young`: Age ≤ 35  
- `Middle Age`: 36–55  
- `Old`: Age > 55

### 📉 Outlier Review
- Verified logical consistency (e.g., `Cars = 0` for `Income > 80k`)
- Scanned for nulls or unusual values, none found

---

## 📊 Visualization and Analysis

### 🧮 Pivot Table (Sheet: `Pivot Table`)
Generated summary tables to analyze:
- % of customers who purchased bikes by:
  - Region
  - Gender
  - Age Bracket
  - Income Range
  - Marital Status

### 📈 Interactive Dashboard (Sheet: `Dashboard`)
Designed a dashboard to visualize:
- Bike purchase distribution across demographics
- Income brackets vs. purchase decisions
- Effects of education and commute distance on bike buying behavior
- Filters/slicers by Region, Gender, Age Bracket

**Visualization Components:**
- Stacked bar charts
- Pie charts for categorical breakdowns
- Slicers for dynamic filtering
- Conditional formatting for highlighting trends

---

## 🧰 Tools Used

- **Microsoft Excel**
  - Text & logical functions: `PROPER()`, `IF()`, `TRIM()`, `VLOOKUP()`
  - Custom columns with formulas
  - Pivot tables and pivot charts
  - Dashboard: slicers, interactive visuals, formatting

---

## 💡 Key Insights

- Higher income individuals are more likely to purchase bikes
- Younger and middle-aged people show higher purchase rates
- Education and occupation type have a noticeable impact on bike ownership
- Commute distance affects the likelihood of bike usage

---

## 🚀 Future Extensions

- Predictive modeling with logistic regression or classification models
- Export cleaned data to Power BI or Tableau for enhanced dashboards
- Use Python or R for advanced analysis (e.g., clustering, correlation heatmaps)
- Integrate survey or GPS data for real-world purchase prediction

---

## 👥 Contributor

- [Azim Nahin](https://github.com/AzimNahin)
---
