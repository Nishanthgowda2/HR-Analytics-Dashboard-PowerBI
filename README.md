# HR-Analytics-Dashboard-PowerBI
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/04f57a76-faee-4a5f-bf12-8afe02012d0f" />


## 📌 Project Overview
Employee attrition is a critical challenge for HR departments.  
This project analyzes **employee attrition trends** and provides actionable insights using Power BI.  

The dashboard helps answer:  
- Which departments and job roles face the highest attrition?  
- How do age, education field, and salary slabs impact attrition?  
- What are the key drivers behind employee turnover?  

---

## 🎯 Problem Statement
To study employee attrition and workforce trends across **departments, age groups, education fields, and salary ranges**, and to design an interactive Power BI dashboard that visualizes these patterns.

---

## 🛠️ Skills & Tools Used
- **Power BI** (Data Import, Power Query, DAX, Dashboard Design)  
- **Data Cleaning** (null handling, duplicates, data type corrections)  
- **DAX Measures**:
  - `Total Employees = DISTINCTCOUNT(EmployeeNumber)`
  - `Employees Left = CALCULATE(DISTINCTCOUNT(EmployeeNumber), HR[Attrition] = "Yes")`
  - `Attrition Rate % = DIVIDE([Employees Left],[Total Employees],0) * 100`
  - `Avg Monthly Income = AVERAGE(MonthlyIncome)`

---

## 📊 Dashboard Features
- **KPI Cards:** Total Employees, Attrition Rate, Average Monthly Income  
- **Donut Chart:** Attrition Rate by Education Field  
- **Clustered Column Chart:** Attrition by Age Group  
- **Bar Chart:** Attrition by Salary Slab  
- **Matrix:** Job Role vs Job Satisfaction  
- **Line Chart:** Attrition trend by Years at Company  
- **Column Chart:** Department vs Employees Left  
- **Slicers:** Gender, Department  

---

## 🔎 Key Insights
- Highest attrition is among employees aged **25–34**.  
- **Lower salary slabs** show higher turnover.  
- Certain job roles have **low satisfaction & high attrition**.  
- A majority of employees exit within the **first 2 years** at the company.  


