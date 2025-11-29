# HR Analytics Dashboard 📈  
A complete Power BI project analyzing workforce patterns, attrition trends, salary insights, and recruitment performance to support data-driven HR decision-making.

---

## 📌 Project Overview
The **HR Analytics Dashboard** provides an interactive and comprehensive view of workforce data, enabling HR teams to identify organizational trends, risks, and opportunities.  
The dashboard offers insights into headcount distribution, attrition rates, demographic patterns, salary trends, and recruitment channel effectiveness.

This project demonstrates practical skills in **Power BI**, **data cleaning**, **DAX modeling**, and **business insights generation**.

---

## 🎯 Objectives
- Analyze employee demographics and department-wise distribution  
- Track hiring trends and attrition behavior over time  
- Identify high-risk areas affecting workforce stability  
- Evaluate recruitment source efficiency  
- Provide actionable insights for HR decision-making  

---

## 🗂 Dataset Information
- **Dataset Name:** HRDataset-v14  
- **Source:** Kaggle  
- **Total Records:** 311 employees  
- **Date Range:** 2008–2015  
- **Key Columns:**  
  - EmployeeID  
  - Department, Position, Employment Status  
  - Age, Gender, Marital Status  
  - Salary  
  - Date of Hire  
  - Recruitment Source  
  - Performance Score  

---

## 🔧 Data Cleaning & Transformation
Performed using **Power Query** in Power BI:

- Verified null values & removed duplicates  
- Corrected data types (Salary → currency, DateOfHire → date, Age → whole number)  
- Validated realistic ranges for age, salary & dates  
- Created calculated column **Age Bucket** (18–25, 26–35, 36–45, 46–55, 55+)  
- Built key **DAX Measures:**  
  - Headcount  
  - Attrition  
  - Attrition %  
  - Average Salary  
  - Average Age  

---

## 📊 Dashboard Features
### 🔹 KPI Cards  
- Total Headcount  
- Attrition Count  
- Attrition Percentage  
- Average Salary  
- Average Age  

### 🔹 Visualizations  
- Headcount by Department  
- Age Distribution by Bucket  
- Gender vs. Marital Status  
- Hiring Trend (Yearly)  
- Attrition Trend  
- Recruitment Source Performance  

### 🔹 Interactivity  
- Slicers: Department, Position, Gender, State, Employment Status  
- Cross-filtering across visuals  
- Drill-through capability  
- Tooltip explanations  

---

## 🚀 Key Insights
- **33.44% attrition rate**, significantly higher than industry benchmarks  
- **67% of workforce** concentrated in the Production department  
- **Average age** of employees is **46.4 years**, indicating an aging workforce  
- Recruitment dominated by **Indeed (28%)** and **LinkedIn (24%)**  
- Hiring surge during **2011–2013** followed by sharp attrition spike  

---

## 📝 Recommendations
- Conduct root-cause analysis for high attrition  
- Strengthen onboarding processes during high hiring periods  
- Promote employee referral programs  
- Develop succession planning for senior workforce  
- Build younger talent pipeline & encourage internal mobility  

---

## 📂 Repository Structure
