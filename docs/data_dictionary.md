# HR Employee Attrition Dataset — Data Dictionary

This dataset contains 1,470 employee records with 35 attributes.  
Source: IBM HR Analytics Employee Attrition Dataset (public).

---

## Variables

- **Age** → Employee age (years)  
- **Attrition** → Whether the employee left the company (Yes/No)  
- **BusinessTravel** → Frequency of business travel (Rarely, Frequently, Non-Travel)  
- **DailyRate** → Daily salary rate (numeric)  
- **Department** → Department (Sales, R&D, HR)  
- **DistanceFromHome** → Distance from home to workplace (miles/km)  
- **Education** → Education level (1=Below College, 2=College, 3=Bachelor, 4=Master, 5=Doctor)  
- **EducationField** → Field of education (Life Sciences, Medical, Marketing, etc.)  
- **EmployeeCount** → Always “1” (redundant field)  
- **EmployeeNumber** → Unique employee ID  
- **EnvironmentSatisfaction** → Satisfaction with workplace environment (1–4)  
- **Gender** → Employee gender (Male/Female)  
- **HourlyRate** → Hourly wage rate  
- **JobInvolvement** → Engagement level (1–4)  
- **JobLevel** → Job seniority level (1–5)  
- **JobRole** → Job title (e.g., Sales Executive, Research Scientist, Manager)  
- **JobSatisfaction** → Satisfaction with job role (1–4)  
- **MaritalStatus** → Marital status (Single, Married, Divorced)  
- **MonthlyIncome** → Monthly salary (numeric)  
- **MonthlyRate** → Monthly pay rate (numeric)  
- **NumCompaniesWorked** → Number of companies worked at before current employer  
- **Over18** → Always “Y” (redundant field)  
- **OverTime** → Works overtime (Yes/No)  
- **PercentSalaryHike** → Percentage salary increase during last appraisal  
- **PerformanceRating** → Performance rating (1–4, most are 3–4)  
- **RelationshipSatisfaction** → Satisfaction with relationships (1–4)  
- **StandardHours** → Always “80” (redundant field)  
- **StockOptionLevel** → Stock option level (0–3)  
- **TotalWorkingYears** → Total years of work experience  
- **TrainingTimesLastYear** → Number of training programs attended last year  
- **WorkLifeBalance** → Work-life balance satisfaction (1–4)  
- **YearsAtCompany** → Number of years at the company  
- **YearsInCurrentRole** → Years in current job role  
- **YearsSinceLastPromotion** → Years since last promotion  
- **YearsWithCurrManager** → Years working with current manager  

---

## Notes
- Some fields (`EmployeeCount`, `Over18`, `StandardHours`) are constant and not useful for analysis.  
- Key target variable = **Attrition**.  
- Dataset is anonymized and safe for public demonstration.

---
