# 📊 Data Preparation & Power BI Analysis

## 1️⃣ Excel Data Cleaning Tasks

- **Standardize Gender**  
  Normalize gender values (e.g., M, F, male, female) to standardized `Male` and `Female`.

- **Unify Training Dates**  
  Convert `Training_Date` entries to a consistent `YYYY-MM-DD` format.

- **Handle Missing or Zero Scores**  
  Identify and address missing or zero values in `Pre_Training_Score` and `Post_Training_Score`.

- **Convert Attendance to Binary**  
  Map attendance values for analysis:  
  - `Yes`, `P` → `1` (Attended)  
  - `No`, `A` → `0` (Missed)

---

## 2️⃣ Power BI Analysis Tasks

### 🔢 Calculated Columns
- **Improvement:** `Post_Training_Score - Pre_Training_Score`
- **Experience Level:** Derived from `Join_Date`  
  (e.g., tenure < 2 years = Junior)

### 📊 Visualizations
- Improvement by **Department** and **Training Program**
- Manager & Peer Feedback Scores by **Education Level**
- Attendance Rate by **Department**

### 🎯 KPI Cards
- Average Improvement
- % of Employees with >20 Improvement
- Average Manager & Peer Feedback Scores

---

## ✅ Deliverables

- Cleaned and standardized dataset (**Excel**)
- Power BI report (`.pbix`) with:
  - Calculated fields
  - Visuals and dashboards
  - KPI cards

---

## 🛠️ Tools

- **Excel:** Data cleaning and preparation
- **Power BI:** Data modeling, visualization, and reporting
