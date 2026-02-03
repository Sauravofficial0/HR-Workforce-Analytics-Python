# 📊 HR Workforce Analytics – Tech Company

A complete end-to-end HR analytics project built using Python (Pandas, NumPy, Matplotlib and Seaborn) to analyze workforce structure, compensation, performance, attrition risk and career growth for a technology company.

This project demonstrates a professional analytics workflow:
data cleaning → validation → business analysis → visualization → HR insights.

---

## 🚀 Project Objective

The objective of this project is to help the HR and leadership team:

- understand workforce composition  
- identify attrition-risk departments  
- evaluate salary structure and fairness  
- analyze productivity and performance patterns  
- assess career growth and promotion delays  

---

## 🗂 Dataset Overview

- Source: HR unstructured dataset (simulated real HR system data)
- Size: 10,000 employee records
- Nature: Unclean, inconsistent and partially missing data
- Type: Employee master data

---

## 📌 Main Columns

- Employee_ID  
- Employee_Name  
- Gender  
- Age  
- Department  
- Job_Title  
- Location  
- Joining_Date  
- Last_Promotion_Date  
- Employment_Type  
- Experience_Years  
- Education_Level  
- Performance_Rating  
- Monthly_Salary  
- Overtime_Hours  
- Absenteeism_Days  
- Manager_ID  
- Attrition_Status  

Cleaned business-ready columns created:

- Gender_clean  
- Employment_Type_clean  
- Attrition_clean  
- Education_clean  
- Location_clean  
- Performance_Rating_clean  
- Years_Since_Promotion  

---

## 🧱 Project Structure



---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔄 Analysis Workflow

1. Data loading and understanding  
2. Data quality checks  
3. Data cleaning and standardization  
4. Handling missing values  
5. Outlier detection (age and experience)  
6. Feature engineering  
7. Exploratory data analysis  
8. HR business visualizations  
9. Final HR insights  

---

# 🧹 Data Cleaning & Preparation

- Q1. Standardize Gender values (M/F → Male/Female) and handle missing values  
- Q2. Standardize Employment_Type (FT → Full-Time, CT → Contract)  
- Q3. Clean Attrition_Status (Y/N → Yes/No)  
- Q4. Handle missing values in Education_Level, Performance_Rating and Location  
- Q5. Detect and treat invalid ages and experience outliers  

---

# 👥 Workforce Composition

- Q6. What is the headcount distribution by department and location?  
- Q7. What is the gender distribution across departments?  
- Q8. Which job titles have the highest number of employees?  
- Q9. What is the age distribution of employees company-wide?  
- Q10. What percentage of employees are Full-Time vs Contract vs Intern?  

---

# 💰 Salary & Compensation Analysis

- Q11. What is the average, median and salary range by department?  
- Q12. Which job titles receive the highest average salary?  
- Q13. Is there a significant salary difference across locations?  
- Q14. Does experience have a correlation with salary?  
- Q15. Does performance rating impact salary?  

---

# ⭐ Performance & Productivity

- Q16. What is the average performance rating by department?  
- Q17. Is overtime linked with higher performance ratings?  
- Q18. Do employees with high absenteeism have lower performance ratings?  
- Q19. Compare performance of employees by employment type.  

---

# 🚪 Attrition & Retention Analysis

- Q20. What is the overall attrition rate?  
- Q21. Which departments have the highest attrition?  
- Q22. Does salary level influence attrition?  
- Q23. Does experience level influence attrition?  
- Q24. Analyze attrition by performance rating and overtime hours.  

---

# ⏳ Career & Growth Analysis

- Q25. What is the average time since last promotion by department and its relationship with attrition?

---

# 📈 Mandatory Visualizations

The following business-critical visualizations are included in the notebook:

- Headcount by department (bar chart)
- Gender distribution across departments (stacked bar chart)
- Salary distribution (histogram and boxplot)
- Experience vs salary (scatter plot)
- Attrition by department (bar chart)
- Performance vs overtime (box plot)
- Absenteeism vs performance (box plot)

---

## 🧠 Key HR Insights (High Level)

- Workforce distribution is uneven across departments.
- Certain departments show consistently higher attrition.
- Salary spread is high even within similar experience groups.
- Higher performance is not necessarily driven by higher overtime.
- Longer promotion gaps show a relationship with higher attrition risk.

---

## 🎯 Business Recommendations

- Review compensation structure in high-attrition departments.
- Introduce structured and transparent promotion review cycles.
- Monitor overtime for high performers to prevent burnout.
- Design targeted retention programs for critical departments.

---

## ▶ How to Run the Project

1. Clone the repository  
2. Open the notebook:


## 📄 Presentation

A business-ready presentation was created from this analysis and can be used directly for HR and leadership review.

---

## 👤 Author

Saurav Chauhan  
Data Analyst  

---

## 📝 Note

This project is designed as a reusable HR analytics pipeline.  
The same notebook can be re-run monthly when new HR data is provided to refresh insights automatically.
