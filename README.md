# 💼 HR Analytics Dashboard - Power BI Project

🔗 **Live Dashboard**:[View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiMmEwZTNiN2ItNTA4YS00ODc3LThhM2ItOTlmYmI5ZGVmZWRhIiwidCI6ImM2NDk4YWJmLWUyOTYtNDkzNy04YzJhLTJmYTlhZDM3YzFjYSJ9)


---

## 📌 Overview

This **HR Analytics Dashboard** project is designed to analyze and visualize key HR metrics to help organizations understand workforce dynamics, employee attrition, and salary distribution. Built using **Power BI**, this dashboard provides actionable insights through interactive visualizations, offering HR managers and business leaders the ability to make data-driven decisions.

---

## 🎯 Objective

To build an interactive and visually engaging HR Analytics dashboard that:
- Tracks employee attrition patterns across various dimensions.
- Identifies areas of concern such as high turnover roles, age groups, salary brackets, and departments.
- Supports HR decision-making through clean and real-time data presentation.

---

## 📊 Key Features

| Metric                     | Description                          |
|---------------------------|--------------------------------------|
| **Total No of Employees** | Total headcount: `1480`              |
| **Average Rating**        | Average rating of employees: `16.08` |
| **Average Age**           | Average employee age: `36.92` years  |
| **Average Salary**        | Average salary: `₹6.5K`              |
| **Company Avg Rating**    | Overall company rating: `7.01`       |

---

## 🔍 Filters Used

- **Department Filter**: Human Resources, Research & Development, Sales
- **Job Role Filter**: All job roles (e.g., Manager, Research Scientist, Sales Executive, etc.)

---

## 📈 Visualizations

### 1. Count Attrition by Education
- Shows distribution of attrition based on education fields:
  - Life Sciences
  - Medical
  - Marketing
  - Technical Degree
  - Other
  - Human Resources

### 2. Count Attrition by Age Group
- Breakdown by age:
  - 18–25: 123
  - 26–35: 611
  - 36–45: 471
  - 46–55: 228
  - 55+: 47

### 3. Count Attrition by Salary
- Salary-wise attrition:
  - Upto ₹5K: 753
  - ₹5K–₹10K: 444
  - ₹10K–₹15K: 150
  - ₹15K+: 133

### 4. Count Attrition by Year
- Time-series line chart displaying attrition over 40 years.

### 5. Count Attrition by Job Role
- Job roles with highest attrition:
  - Sales Executive: 329
  - Research Scientist: 293
  - Laboratory Technician: 261

### 6. Job Role-wise Rating Table
- Table showing employee distribution across rating levels (1–4) by job roles.

---

## 🧠 Insights

- Majority attrition is among employees aged 26–35.
- Highest attrition roles: **Sales Executive** and **Research Scientist**.
- Most attrition comes from employees earning **below ₹5K**.
- Employees with **Life Sciences** education tend to leave more.
- **Research & Development** department sees highest attrition.

---

## 🛠️ Tools Used

| Tool               | Purpose                                     |
|--------------------|---------------------------------------------|
| **Power BI Desktop** | Data modeling, DAX, and visualizations      |
| **Power Query Editor** | Data cleaning and transformation         |
| **Power BI Service** | Dashboard publishing and sharing           |
| **DAX**             | Measures and calculated columns             |
| **Slicers**         | Interactive filtering of dashboard visuals  |

---

## 📦 Data Source

- Synthetic HR dataset containing:
  - Employee ID
  - Age, Salary, Job Role, Department
  - Attrition Status
  - Education, Years of Experience
  - Performance Ratings

