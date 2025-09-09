📊 HR Analytics Dashboard – Employee Turnover Case Study  

🔹 Objective  
The goal of this project is to analyze employee turnover data using **SQL** and **Power BI** to identify key drivers of attrition, provide actionable insights, and help HR managers design retention strategies.  

---

🔹 Data Source  
- Dataset: HR Employee Turnover (from Kaggle)  
- Rows: ~15,000 employees  
- Columns: Employee satisfaction, evaluation scores, projects, working hours, tenure, promotions, salary, department, attrition flag  

---

🔹 Tools Used  
- SQLite – Data cleaning & exploratory SQL queries  
- Power BI – Data modeling, calculated columns, DAX measures, interactive dashboard creation  

---

🔹 Data Preparation  
1. Imported raw CSV into SQLite and ran SQL queries to explore attrition patterns.  
2. Loaded cleaned dataset into Power BI.  
3. Created custom calculated columns for better analysis:  
   - **TenureGroup** → Categorized employees by years at company (`<=2`, `3–5`, `>5`)  
   - **AttritionLabel** → Converted binary attrition flag (0/1 → Stayed/Left)  
   - **SatisfactionBand** → Classified employees into Low / Medium / High satisfaction  

4. Built DAX measures:  
   - `Total Employees`  
   - `Employees Left`  
   - `Attrition Rate`  
   - `Average Satisfaction`  
   - `Average Monthly Hours`  

---

🔹 Dashboard Overview  
Key KPIs displayed at the top:  
Total Employees  
Employees Left 
Attrition Rate (%) 
Average Satisfaction 
Average Monthly Hours  

Filters: Department, Salary, Tenure Group, Attrition Status  

Visuals:  
- Attrition by Department  
- Attrition by Salary Level  
- Attrition by Tenure Group  
- Attrition by Satisfaction Level (donut chart)  
- Attrition by Promotion (Last 5 Years)  
- Attrition by Work Accident  

---

🔹 Key Insights  
1. Departments: Sales, Technical, and Support see the highest attrition.  
2. Salary: Employees with low salaries account for the majority of attrition.  
3. Tenure: Employees with 3–5 years at the company are most likely to leave.  
4. Promotion: Employees without promotions in the last 5 years are far more likely to exit.  
5. Satisfaction: Majority of employees who left reported low satisfaction(<0.4).  
6. Work Accident: Accident history has minimal correlation with attrition.  

---

🔹 Business Recommendations  
Based on the analysis, HR managers should focus on:  
-Compensation: Reassess salary structure for low-paid employees.  
-Career Growth: Provide promotion and upskilling opportunities, especially for 3–5 year tenure employees.  
-Department Focus: Prioritize retention strategies in Sales and Technical teams.  
-Employee Engagement: Regular feedback surveys and recognition programs to boost satisfaction.  

---

🔹 Project Outcome  
-  Built an interactive HR Analytics dashboard with drilldowns by salary, tenure, and department.  
-  Delivered actionable insights for strategic HR decision-making.  
-  Demonstrated end-to-end data analysis workflow: SQL → Power BI → Insights → Recommendations.  

---

🔹 Dashboard Preview  
![Dashboard Screenshot](dashboard.png)  


---

🔹 Author  
Project by Aadya Agarwal | SQL & Power BI Enthusiast | Data Analyst
---
