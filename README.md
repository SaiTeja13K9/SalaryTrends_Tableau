# SalaryTrends_Tableau

# Exploring Global Data Companies Salary Trends  

## Table of Contents  
- [Introduction](#introduction)  
- [Variable Insights](#variable-insights)  
- [Rationale Behind Data Selection](#rationale-behind-data-selection)  
- [Problem Statement](#problem-statement)  
- [Analysis](#analysis)  
- [Visualizations](#visualizations)  
- [Dashboards](#dashboards)  
- [Business Implications](#business-implications)  
- [Conclusion](#conclusion)  
- [References](#references)  

## Introduction  
The project **"Exploring Global Data Companies Salary Trends"** focuses on salary trends within global data companies, capturing various factors influencing salaries across data industries worldwide. This project utilizes a dataset containing salary information in business intelligence and data science sectors.  

Key insights explored:  
- **Regional salary differences** across countries and continents.  
- **Salary distributions among different roles**, such as Data Analyst, Data Scientist, BI Developer, etc.  
- **Experience level correlation** with salary variations.  
- **Salary structures based on company size and location.**  
- **Visualized salary trends over time.**  

## Variable Insights  
The dataset includes key variables crucial for analyzing salary trends:  
- **Job Title:** Differentiates positions such as Data Scientist, Data Engineer, and BI Developer.  
- **Company Size:** Categorized into Small, Medium, and Large.  
- **Experience Level:** Entry, Mid, Senior, and Executive.  
- **Location:** Reflects salary variations based on geography.  
- **Employment Type:** Full-time, Part-time, and Contract-based.  
- **Annual Salary (USD):** The primary dependent variable.  

These variables enable a **transparent and equitable** salary analysis within the tech sector.  

## Rationale Behind Data Selection  
The dataset helps analyze **pay trends**, **experience-based salary growth**, **organizational impact on compensation**, and **regional pay differences**. This project benefits stakeholders like **job seekers, employers, policymakers, and educational institutions** by identifying trends and evaluating the demand for specific data roles.  

## Problem Statement  
Despite the data industry’s rapid economic growth, salary disparities persist due to **location, job function, company size, and experience level**. This project aims to:  
1. Understand why these salary differences exist.  
2. Promote **fairer compensation structures**.  
3. Provide **data-driven recommendations** for hiring strategies and salary negotiations.  

## Analysis  
**Key insights:**  
- The dataset consists of **3,300 records from 2020 to 2023**.  
- Most job titles are **Data Engineer and Data Scientist** roles.  
- The average salary is **$142,096** with a standard deviation of **$69,028**, indicating salary dispersion.  
- **Salaries increase with experience and company size.**  
- **Regional differences exist**, with higher salaries in the U.S. and parts of Europe.  

---

## Visualizations  

### 1. Average Salaries by Employment Type (2020-2024)  
This visualization tracks salary changes for **Full-time, Part-time, and Contract** employees over time.  

![Employment Type Salary Trends](screenshots/employment_type_salary_trends.png)  

- Full-time salaries peaked in 2022 before declining.  
- Part-time salaries remained relatively stable.  
- Freelancers consistently earned **less than full-time or part-time employees**.  

---

### 2. Total Salaries by Company Size and Expertise Level  
This heatmap visualizes how company size affects salary distribution among **Entry, Intermediate, Expert, and Director** levels.  

![Salary by Company Size](screenshots/salary_by_company_size.png)  

- Large companies prioritize **expert-level** professionals.  
- Medium-sized firms **invest more in mid-level employees**.  
- Small companies maintain **even salary distributions** across all levels.  

---

### 3. Salary Trends by Expertise Level  
Box plots illustrate **salary variations between Experts and Juniors**.  

![Expert vs. Junior Salaries](screenshots/expert_vs_junior_salaries.png)  

- Experts have **higher salary dispersion** with top outliers.  
- Juniors have a **narrower salary range**, indicating fixed pay scales.  

---

### 4. Maximum Salary by Company Location  
A **global map** displaying salary distribution across different countries.  

![Global Salary Map](screenshots/global_salary_map.png)  

- **Europe and the U.S.** have the highest salaries.  
- Asia shows **lower salary distributions** in comparison.  

---

### 5. Treemap of Salaries by Job Type  
The treemap presents **average salaries** across employment types and experience levels.  

![Treemap Salary Distribution](screenshots/treemap_salary_distribution.png)  

- **Freelance Mid-level professionals earn the highest salaries** (~$520,311).  
- Executive-level salaries vary significantly.  

---

### 6. Salary Distribution in Business Intelligence (BI) Roles  
A **donut chart** depicting total salary distribution across different company sizes.  

![BI Salary Distribution](screenshots/bi_salary_distribution.png)  

- Large companies dominate BI salary expenditure (~72.82%).  
- Small companies contribute **only 1.83%** to total BI salaries.  

---

### 7. Bullet Chart Comparing Median vs. Average Salaries  
This bullet chart highlights **salary skewness** in BI roles.  

![Median vs. Average Salaries](screenshots/median_vs_average_salaries.png)  

- A significant **gap between median and average salaries** indicates outliers pulling up the average.  

---

## Dashboards  

### **Dashboard 1: BI Salary Growth Over Time**  
- Highlights **full-time BI professionals** with **mid-level salaries peaking at $1.44M**.  
- Demonstrates **strong salary growth trends in BI fields**.  

![BI Salary Growth Dashboard](screenshots/bi_salary_growth_dashboard.png)  

### **Dashboard 2: Salary by Company Size & Location**  
- **Medium-sized companies pay the highest salaries** to experts.  
- Some **unexpected locations (e.g., Chile) show extremely high salaries**.  

![Company Size Salary Trends](screenshots/company_size_salary_trends.png)  

### **Dashboard 3: Salary Distribution in BI Roles**  
- **Freelance Mid-level and Full-Time Executive** roles earn the highest pay.  

![BI Role Salary Distribution](screenshots/bi_role_salary_distribution.png)  

---

## Business Implications  
### **Data-Driven Decision Making**  
- Helps **companies set competitive salaries**.  
- Assists HR teams in **negotiating fair pay scales**.  
- **Identifies high-value roles** in the market.  

### **Strategic Insights for Workforce Planning**  
- Large companies **invest heavily in experts**, while smaller firms **pay evenly across experience levels**.  
- Salaries for **BI professionals are rising**, making it a lucrative field.  

### **Budget Allocation & Hiring Strategies**  
- Companies can use these insights to **optimize salary structures**.  
- Helps **job seekers target high-paying roles & locations**.  

---

## Conclusion  
The **Exploring Global Data Companies Salary Trends** project:  
✅ **Identifies pay disparities** based on job role, company size, and location.  
✅ **Helps businesses optimize salary structures** using data-driven insights.  
✅ **Empowers job seekers** by revealing **market salary trends**.  
✅ **Enables strategic workforce planning** in data-related fields.  

---

## References  
1. Kaggle Dataset: ["Latest Data Science Salaries"](https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023)  
2. Ohmann, A., & Floyd, M. (2015). *Creating Data Stories with Tableau Public*.  
3. Batt, S., et al. (2020). *Learning Tableau: A Data Visualization Tool*.  

---

### 🚀 **How to Run This Project**
1. Clone this repository:  
   ```sh
   git clone https://github.com/your-repo-name.git
