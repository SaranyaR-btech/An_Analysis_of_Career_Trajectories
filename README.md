# An Analysis of Career Trajectories
## Industry Insights from a Global Salary Survey

---

## 📌 Objectives

- Analyze salary distribution across demographics and roles
- Explore the influence of education and experience on compensation
- Identify gender-based and geographic disparities
- Create visual dashboards to communicate key insights

---

## 🧾 Dataset Overview

- **Rows:** 28,104  
- **Columns:** 16  
- Key attributes:
  - Job Title, Industry, Annual Salary
  - Country, City, Gender
  - Education, Experience (Overall & Field)
  - Additional Monetary Compensation

---

## 🔍 Data Cleaning

- Removed rows with missing values in:
  - Years of Experience (Overall & In-Field)
  - Education Level
  - Gender
- Filled other missing values:
  - Categorical → `"Unknown"`
  - Numerical → `0`
- Standardized job titles, countries, and currencies

---

## ⚙️ Feature Engineering

- Created **`Industry Category`** to group similar industries
- Created **`Salary_in_USD`** using **VLOOKUP** based on currency conversion rates

---

## 🗃️ SQL Queries

Performed 10 SQL queries to explore:

1. Average Salary by Industry and Gender  
2. Total Compensation by Job Title  
3. Salary by Education Level  
4. Median Salary by Age and Gender  
5. Employees by Industry & Experience  
6. Highest Paying Job Titles by Country  
7. Average Salary by City and Industry  
8. % with Additional Compensation by Gender  
9. Total Compensation by Experience Level  
10. Average Salary by Industry, Gender, Education

---

## 📊 Dashboard Highlights

- Built using Excel (Pivot Tables & Charts)
- Visualized:
  - Salary by industry, job title, and country
  - Gender distribution
  - Compensation by education and experience
- Interactive filters for dynamic analysis

---

## ✅ Tools Used

- **Excel** (Data cleaning, visualization)
- **MySQL** (Database queries)
- **VLOOKUP** (Currency conversion)
- **Pivot Tables & Charts** (Dashboards)

---

## 📌 Deliverables

- Cleaned dataset  
- MySQL database + 10 queries  
- Excel workbook with analysis sheets  
- Final dashboard  
- Presentation (.pptx)  
- Project report (PDF)

---

## 📊 Dashboard


https://github.com/user-attachments/assets/098eac89-2c7d-4196-86c2-e9adfadf18f9



## 📎 License

This project is for academic and educational purposes only.

---


