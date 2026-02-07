# NREGA Excel Dashboard Project
## Project Overview
link - C:\Users\panka\OneDrive\Pictures\Screenshots\excel_dashboard.png
This project involves creating an **interactive Excel dashboard** using the **NREGA (Mahatma Gandhi National Rural Employment Guarantee Act) dataset**. The dashboard helps analyze employment generation, worker participation, expenditure patterns, and work completion status across Indian states and districts.

The project is designed for **academic use, data analysis practice, and portfolio presentation**.

---

##  Objectives

* Analyze total and active workers under NREGA
* Compare job cards issued vs active utilization
* Study expenditure distribution (wages, material, administrative)
* Evaluate women, SC, and ST participation
* Assess completed vs ongoing works
* Build KPI-driven, interactive Excel dashboard

---

##  Dataset Description

**Source:** NREGA public data (CSV format)

### Key Columns Used:

* State Name
* District Name
* Total No. of Workers
* Total No. of Active Workers
* Total No. of Job Cards
* Women Persondays
* SC Persondays
* ST Persondays
* Wages (Rs. in Lakhs)
* Material and Skilled Wages (Rs. in Lakhs)
* Administrative Expenditure (Rs. in Lakhs)
* Number of Ongoing Works
* Number of Completed Works

---

## 🛠 Tools & Technologies

* **Microsoft Excel**

  * Pivot Tables
  * Pivot Charts
  * KPI Cards
  * Slicers
  * Data Cleaning Tools

---

## ⚠️ Data Cleaning Note

Since the dataset was imported from a **CSV file**, many numeric columns were initially stored as **text**, causing formulas like `SUM()` to return **0**.

### Fix Applied:

* Converted text to numbers using:

  * **Data → Text to Columns → General**
  * OR **Paste Special → Multiply**

This step ensured accurate KPI calculations and chart analysis.

---

## 📈 KPIs Created

* Total Workers
* Active Workers
* Total Job Cards
* Total Expenditure (₹ Lakhs)
* Completed Works

Each KPI is displayed as a **card** at the top of the dashboard for quick insights.

---

## 📊 Charts & Analysis

### 1. Workers by State (Bar Chart)

* Identifies states with highest employment demand

### 2. Active Workers vs Job Cards (Clustered Column)

* Measures job card utilization efficiency

### 3. Expenditure Breakdown (Stacked Column)

* Shows dominance of wage expenditure in NREGA

### 4. Women Participation (Column Chart)

* Highlights women empowerment through rural employment

### 5. Completed vs Ongoing Works (Column Chart)

* Evaluates implementation and completion efficiency

---

##  Interactivity Features

* **Slicers** for:

  * State
  * District
* All charts and KPIs update dynamically based on selections

---

##  Key Insights

* Higher worker participation in rural-focused states
* Strong women participation in persondays
* Majority expenditure allocated to wages, aligning with NREGA objectives
* Completion rates vary significantly across states

---

##  Conclusion

The Excel dashboard provides a **clear, interactive, and data-driven overview** of NREGA performance. It demonstrates the effective use of Excel for public policy analysis and social sector data visualization.

---

##  Author

**Simi Dubey**

---

##  Usage

This project can be used for:

* Academic submission
* Data analysis practice
* Resume/portfolio project
* Viva and presentation demonstrations

---
