# Workforce360 HR Data Insights

## 📝 Objective
The HR Analytics Dashboard is designed to provide insights into employee attrition and workforce characteristics. It helps HR teams and management understand patterns behind employee turnover, salary distribution, job roles, and demographics, enabling better decision-making and retention strategies.

## 🎯 Goals
* Track total employee count, attrition rate, average age, average salary, and years of service.

* Identify attrition patterns by department, education field, job role, salary bracket, and tenure.

* Provide interactive filtering capabilities by job role and department.

* Support strategic HR initiatives, including retention planning, compensation strategy, and workforce diversity analysis.

## 📈 Key KPIs
1. Attrition Rate = (CALCULATE(count(HR_Analytics[EmpID]),HR_Analytics[Attrition]="Yes")/COUNT(HR_Analytics[EmpID]))*100 

2. Average Age = AVERAGE(HR_Analytics[Age])

3. Average Salary = AVERAGE(HR_Analytics[MonthlyIncome])
   
4. Average_years_at_Company = AVERAGE(HR_Analytics[YearsAtCompany])
  
## 📊 Visuals & Insights
1. Attrition by Education Field (Donut Chart)
    * Breaks down attrition count by education field (e.g., Life Sciences, Medical, Technical Degree, Marketing).
    * Helps analyze which educational backgrounds have higher turnover.

2. Attrition by Age Group (Bar Chart)
    * Groups employees into age brackets (18–25, 26–35, 36–45, etc.).
    * Shows attrition is highest in the 26–35 group, indicating mid-career turnover risk.

3. Attrition by Job Role (Bar Chart + Matrix)
    * Compares attrition across different job roles (Sales Executive, Research Scientist, Manager, etc.).
    * Matrix table shows counts by job role and attrition category.
    * Useful to pinpoint high-turnover roles (e.g., Sales & Research).

4. Attrition by Salary Slab (Bar Chart)
    * Groups salary ranges into slabs (Up to 5k, 5k–10k, 10k–15k, 15k+).
    * Shows lower salary bands have higher attrition → signals compensation-related turnover.

5. Attrition by Years at Company (Line Chart)
    * Displays attrition trend across tenure years.
    * Attrition spikes during early years of employment, then stabilizes → highlights onboarding & engagement gaps.
  
