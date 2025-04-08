# 🚲 Bike Buyers – Data Cleaning and Visualization (Excel Project)

This project demonstrates a comprehensive **data preprocessing and summarization workflow** using **Microsoft Excel** on a customer dataset related to bike purchases. The dataset comprises demographic, economic, and behavioral data for over 1000 individuals. All transformations and visual summaries were performed within Excel, making this project a fully no-code analytical solution.

---

## 🎯 Project Objectives

- Clean and standardize raw customer data
- Translate encoded fields into readable categories
- Derive new categorical groupings (e.g., age brackets)
- Summarize trends using pivot tables
- Lay the foundation for dashboard-based visualization

---

## 📁 Dataset Description

The original dataset, located in the **`bike_buyers`** sheet, contains **1026 records** and **13 columns**, including:

| Column Name         | Description |
|---------------------|-------------|
| `ID`                | Customer ID |
| `Marital Status`    | Encoded as `M` (Married) or `S` (Single) |
| `Gender`            | Encoded as `M` (Male) or `F` (Female) |
| `Income`            | Annual income in USD |
| `Children`          | Number of children |
| `Education`         | Highest academic attainment |
| `Occupation`        | Professional category |
| `Home Owner`        | Whether the customer owns a home (`Yes`/`No`) |
| `Cars`              | Number of cars owned |
| `Commute Distance`  | Commute range (e.g., `0-1 Miles`, `5-10 Miles`) |
| `Region`            | Geographical region |
| `Age`               | Customer’s age |
| `Purchased Bike`    | Whether the customer purchased a bike (`Yes`/`No`) |

---

## 🧹 Data Cleaning and Transformation (`Working Sheet`)

The cleaned dataset is presented in the **`Working Sheet`** with **1000 records** and **14 columns**. Cleaning and transformation steps include:

### 🔄 Encoding Normalization
- `Marital Status`: M → Married, S → Single  
- `Gender`: M → Male, F → Female

### 🧼 Standardization
- Used `PROPER()` and `TRIM()` to clean inconsistent casing and extra whitespace
- Ensured uniformity across categorical values

### 🧒 Age Categorization
- Added a new column, `Age-Brackets`, grouped as:
  - **Adolescent**: Youngest segment (label found in pivot)
  - **Middle Age**: Working-age individuals
  - **Old**: Customers above midlife

> Note: Labels used are as reflected in pivot tables.

---

## 📊 Pivot Table Analysis (`Pivot Table` Sheet)

Three pivot tables were created to summarize the dataset from different perspectives:

### 📌 1. Average Income by Gender and Purchase Decision
- **Rows**: Gender (`Male`, `Female`)
- **Columns**: `Purchased Bike` (`Yes`, `No`)
- **Values**: Average of `Income`
- **Insight**: Highlights income variation across gender and bike purchase behavior

### 📌 2. Bike Purchases by Commute Distance
- **Rows**: Commute Distance (e.g., `0-1 Miles`, `5-10 Miles`, `More than 10 Miles`)
- **Columns**: `Purchased Bike`
- **Values**: Count of records
- **Insight**: Shows how commuting distance correlates with bike purchasing

### 📌 3. Bike Purchases by Age-Bracket
- **Rows**: `Age-Brackets` (`Adolescent`, `Middle Age`, `Old`)
- **Columns**: `Purchased Bike`
- **Values**: Count of records
- **Insight**: Reveals which age groups are most likely to purchase bikes

Each pivot table includes Grand Totals for comprehensive comparison.

---

## 📈 Dashboard Initialization (`Dashboard` Sheet)

The **`Dashboard`** sheet contains the title header:  
📌 **"Bike Sales Dashboard"**

At present, no visual elements (charts/slicers) are populated, but the layout is ready for expansion using:
- Pivot charts
- Slicers for interactive filtering
- Conditional formatting and layout enhancements

---

## 🛠 Tools and Techniques Used

- **Microsoft Excel**
  - Data cleaning using: `IF()`, `PROPER()`, `TRIM()`
  - Manual and formula-based transformation
  - Pivot Tables for aggregation and summarization
  - Sheet organization for reporting

---

## 📌 Key Outcomes

- Cleaned and structured a raw customer dataset using Excel-only techniques
- Created age-based segmentation and corrected encoded fields
- Developed three analytical pivot tables
- Initiated a structured dashboard sheet for future visualization development

---

## 👤 Contributor
- [Azim Nahin](https://github.com/AzimNahin)
---
