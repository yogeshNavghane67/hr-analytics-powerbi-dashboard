# hr-analytics-powerbi-dashboard

## 📌 Project Overview
An interactive **HR Analytics Dashboard** built in **Microsoft Power BI** to analyze employee attrition, workforce demographics, job satisfaction, and retention drivers. This project transforms raw HR data into actionable insights, enabling HR teams and leadership to identify high-risk attrition segments and optimize talent retention strategies.

<img width="1317" height="736" alt="Screenshot 2026-11-25 010607" src="https://github.com/user-attachments/assets/e1d7a887-d289-452d-ae74-773c8d1214e2" />

---

## 🎯 Business Objectives
- Track overall **Employee Headcount**, **Attrition Count**, **Attrition Rate**, and **Active Employees**.
- Identify key factors contributing to employee turnover across **Departments**, **Job Roles**, **Age Groups**, and **Salary Slabs**.
- Evaluate **Job Satisfaction**, **Work-Life Balance**, and **Environment Satisfaction** ratings across tenure brackets.
- Provide dynamic filtering by gender, education field, marital status, and business travel frequency.

---

## 📂 Dataset Overview
- **Source:** HR Employee Attrition Dataset *(Update with your exact source, e.g., IBM HR Analytics / Kaggle)*
- **Total Records:** ~1,470 employees *(Update with your exact row count)*
- **Key Attributes:**
  - **Demographics:** Age, Gender, Marital Status, Education, Education Field, Distance from Home.
  - **Employment Details:** Department, Job Role, Job Level, Years at Company, Years in Current Role, Business Travel.
  - **Compensation & Satisfaction:** Monthly Income, Salary Hike %, Job Satisfaction, Environment Satisfaction, Performance Rating, Overtime.
  - **Target Metric:** Attrition (`Yes` / `No`).

---

## 🛠️ Tools & Techniques Used
- **Power Query (ETL):** Data cleaning, null handling, data type formatting, and custom conditional columns (e.g., *Age Groups*, *Tenure Brackets*, *Salary Slabs*).
- **Data Modeling:** Structured relationships and dedicated DAX Measures table.
- **DAX (Data Analysis Expressions):** Custom calculated measures for dynamic KPIs and percentage ratios.
- **Data Visualization:** KPI cards, Donut charts, Clustered Bar/Column charts, Matrix tables, and interactive Slicers.

---
