# 🚲 Bike Buyers – Data Cleaning and Visualization (Excel Project)

This project presents a complete data preparation and visualization workflow using **Microsoft Excel**. The dataset comprises customer information related to bike purchases, including demographic, behavioral, and regional attributes. All data cleaning, transformation, and visual analysis were conducted in Excel, making this a comprehensive no-code data analytics project.

---

## 🎯 Project Objectives

- Clean and standardize a raw dataset for business analysis
- Transform encoded categorical data into human-readable formats
- Derive new features (e.g., age group segmentation)
- Generate pivot tables for analytical insights
- Design an interactive Excel dashboard for stakeholder presentation

---

## 📁 Dataset Overview (`bike_buyers` Sheet)

The dataset contains **1026 customer records** and **13 attributes**:

| Column              | Description                                                  |
|---------------------|--------------------------------------------------------------|
| `ID`                | Unique customer identifier                                   |
| `Marital Status`    | Encoded as `M` (Married) or `S` (Single)                     |
| `Gender`            | Encoded as `M` (Male) or `F` (Female)                        |
| `Income`            | Annual income in USD                                         |
| `Children`          | Number of children                                           |
| `Education`         | Highest academic qualification                               |
| `Occupation`        | Profession type (e.g., Professional, Clerical)              |
| `Home Owner`        | Homeownership status (`Yes`/`No`)                            |
| `Cars`              | Number of cars owned                                         |
| `Commute Distance`  | Distance between home and workplace (e.g., `0-1 Miles`)      |
| `Region`            | Geographic region (e.g., Europe, Pacific)                    |
| `Age`               | Age of the individual                                        |
| `Purchased Bike`    | Target variable – whether the customer purchased a bike      |

---

## 🧹 Data Cleaning and Transformation (`Working Sheet`)

The `Working Sheet` contains the cleaned and enhanced dataset with **1000 rows** and **14 columns**, including the following transformations:

### ✅ Categorical Normalization
- `Marital Status`: M → Married, S → Single  
- `Gender`: M → Male, F → Female  
- Applied `PROPER()` and `TRIM()` functions for consistent text formatting

### 🧒 Age Binning
Added a new column: **`Age-Brackets`** with the following categories:
- `Adolescent` – younger individuals
- `Middle Age` – between early adulthood and midlife
- `Old` – senior individuals

These were categorized to support demographic segmentation in analysis and dashboards.

---

## 📊 Pivot Table Analysis (`Pivot Table` Sheet)

Three detailed pivot tables were developed to uncover insights into bike buying behavior:

### 📌 1. Average Income by Gender and Purchase Status
- **Row Labels**: Gender (Male, Female)
- **Column Labels**: Bike Purchase (`Yes`, `No`)
- **Values**: Average of Income  
- **Insight**: Compare income levels across genders and their likelihood to purchase bikes

### 📌 2. Bike Purchases by Commute Distance
- **Row Labels**: Commute Distance (e.g., `0-1 Miles`, `More than 10 Miles`)
- **Column Labels**: Purchased Bike (`Yes`, `No`)
- **Values**: Count of records  
- **Insight**: Evaluate how commuting range affects purchase behavior

### 📌 3. Bike Purchases by Age-Bracket
- **Row Labels**: Age Brackets (`Adolescent`, `Middle Age`, `Old`)
- **Column Labels**: Purchased Bike (`Yes`, `No`)
- **Values**: Count of records  
- **Insight**: Identify the most likely customer age group to purchase bikes

Each pivot includes **grand totals** for high-level comparison.

---

## 📈 Interactive Dashboard (`Dashboard` Sheet)

The `Dashboard` sheet hosts a fully functional Excel dashboard titled **"Bike Sales Dashboard"**. It visually represents insights using charts and filters for real-time exploration.

### Included Features:
- **📊 Pivot Charts**:
  - Bike purchases by gender
  - Bike purchases by age bracket
  - Commute distance vs. purchase decision

- **🧩 Slicers**:
  - Marital Status
  - Education
  - Region
  - Children

These tools allow users to filter data dynamically and gain actionable insights through simple clicks — no code or formula writing required.

---

## 🛠 Tools and Techniques Used

- **Microsoft Excel**
  - `IF()`, `PROPER()`, `TRIM()` for categorical transformation
  - Custom column creation (Age Brackets)
  - Pivot tables for aggregation and analysis
  - Pivot charts and slicers for dashboard interactivity
  - Sheet formatting and layout design for clarity and usability

---

## 📌 Key Outcomes

- Cleaned and standardized a customer dataset using Excel
- Transformed encoded fields into meaningful labels
- Developed demographic-based segmentation features
- Designed three pivot tables for data-driven insights
- Built an interactive dashboard to support decision-making and reporting

---

## 👥 Contributor
- [Azim Nahin](https://github.com/AzimNahin)

---
