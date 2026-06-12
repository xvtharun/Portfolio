# HR Analytical Dashboard 📊

## 📌 Project Overview

This project is an HR Analytics Dashboard created to analyze employee attrition, workforce demographics, job satisfaction, and department-wise employee trends.

The dashboard helps HR teams and management understand the major factors affecting employee retention and organizational performance.

> **Dataset:** [Kaggle HR Analytics Dataset](https://www.kaggle.com/) — visualized using Power BI.

---

## 📊 Dashboard Preview

![HR Analytics Dashboard](hr_analytical_dashboard.png)

https://www.youtube.com/watch?v=dOWOQHQkXXo

---

## 🎯 Objective

- Analyze employee attrition trends
- Improve workforce decision-making
- Identify departments with high attrition
- Understand demographic-based employee patterns

---

## 📈 Key Insights

| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16.12% |
| Active Employees | 1,233 |
| Average Employee Age | 37 |

### Observations
- Employees with a **Bachelor's Degree** show the highest attrition.
- The **25–34 age group** has the maximum employee attrition.
- **Sales and R&D** departments contribute the highest attrition rates.
- **Male employees** account for a higher attrition percentage compared to female employees.

---

## 🚀 Features

- Total Employee Analysis
- Attrition & Attrition Rate Tracking
- Active Employees Overview
- Job Satisfaction Rating
- Gender Distribution Analysis
- Education-wise Attrition
- Department-wise Attrition
- Attrition by Job Role
- Attrition by Age Group
- Attrition by Years at Company
- Attrition by Salary Hike
- Interactive Filter / Slicer Panel

---

## 📷 Dashboard Components

| Visual | Type | Description |
|---|---|---|
| Total Employees | KPI Card | Overall headcount |
| Total Attrition | KPI Card | Number of employees who left |
| Attrition % | KPI Card | Attrition rate as a percentage |
| Average Age | KPI Card | Mean age across the workforce |
| Average Salary | KPI Card | Mean monthly income |
| Attrition by Education Field | Donut Chart | Attrition distribution across education backgrounds |
| Attrition by Job Role | Column Chart | Attrition count per job role |
| Attrition by Age | Bar Chart | Attrition segmented by age band |
| Attrition by Years at Company | Line Chart | Tenure trend and attrition relationship |
| Attrition by Salary Hike | Funnel | Attrition across salary hike percentage brackets |
| Attrition by Job Satisfaction | Pivot Table | Matrix of attrition vs. satisfaction rating per role |
| Education Field Filter | Slicer | Dynamically filters all visuals |

---

## 📂 Data Model

The report is built on a single table — **`Data`** — with the following fields:

| Field | Description |
|---|---|
| `Attrition` | Whether the employee left (Yes/No) |
| `CF_attrition count` | Calculated numeric attrition flag (1/0) |
| `Attrition_perc` | Calculated attrition rate percentage |
| `Age` | Employee age |
| `CF_age band` | Calculated age group/band |
| `Department` | Department the employee belongs to |
| `Education Field` | Employee's educational background |
| `Employee Count` | Total employee count |
| `Job Role` | Job title/role |
| `Job Satisfaction` | Job satisfaction score |
| `Monthly Income` | Employee's monthly salary |
| `Percent Salary Hike` | Last salary hike percentage |
| `Years At Company` | Tenure in years |

---

## 📌 KPIs Used

- Total Employees
- Attrition Count
- Attrition Rate
- Active Employees
- Average Age
- Average Salary
- Job Satisfaction Score

---

## 🛠️ Tools & Technologies

- **Power BI** (v2.152.856.0) — Dashboard creation & visualization
- **Microsoft Excel / CSV** — Data preparation
- **Kaggle** — Dataset source
- Data Cleaning & Visualization Techniques

---

## 🚀 How to Open

1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Open the `.pbix` file via **File → Open report → Browse this device**.
3. The report opens with all data embedded — no additional configuration required.

To publish online, go to **Home → Publish** and select your Power BI workspace.

---

## 🔮 Future Improvements

- Add predictive attrition analysis using Machine Learning
- Include salary and performance correlation analysis
- Add real-time database connectivity
- Improve mobile responsiveness
- Department-level drill-through pages

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!
