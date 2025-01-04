# **HR Analytics Dashboard for Atlas Labs**

## **Introduction**
Employee attrition is a significant challenge for organizations, leading to increased costs for recruitment, training, and productivity loss. This project focuses on analyzing employee performance, demographics, and attrition trends at Atlas Labs. Using Power BI, we aim to:
- **Understand workforce trends**: Analyze employee demographics, satisfaction, and performance metrics.
- **Identify attrition drivers**: Explore factors like job roles, overtime, and satisfaction levels contributing to attrition.
- **Support data-driven decisions**: Provide actionable insights to improve employee retention and satisfaction.

This project enables the HR team to make informed decisions and optimize workforce management strategies.

---

## **Analysis**

### **Visualizations and Their Purpose**

1. **Overview Dashboard**
   - **Metrics**: Total Employees, Active Employees, Inactive Employees, Attrition Rate (16.1%).
   - **Visualizations**:
     - **Employee Hiring Trends**: Bar chart showing hiring trends over the years with attrition labels (Yes/No).
     - **Active Employees by Department**: Bar chart showing department-wise employee distribution.
     - **Active Employees by Job Role**: Tree map visual of employees categorized by department and job role.
   - **Purpose**:
     - Provides a high-level summary of workforce composition and attrition trends.
     - Helps identify departments and roles with high attrition rates.

2. **Demographics Dashboard**
   - **Metrics**: Youngest Employee (18 years), Oldest Employee (51 years), and employee distribution by age, marital status, and ethnicity.
   - **Visualizations**:
     - **Employees by Age Group**: Bar chart categorizing employees into age brackets.
     - **Employees by Marital Status**: Pie chart showing marital status distribution.
     - **Employees by Ethnicity and Average Salary**: Combined bar and line chart showing ethnicity distribution and average salaries.
   - **Purpose**:
     - Understand workforce diversity and salary trends.
     - Identify demographic groups that might require targeted support or resources.

3. **Performance Tracker**
   - **Metrics**: Employee-specific data on satisfaction levels (Job Satisfaction, Work-Life Balance, Manager Rating, etc.).
   - **Visualizations**:
     - Line charts tracking satisfaction metrics over the years for selected employees.
     - Ratings categorized from "Very Dissatisfied" to "Very Satisfied."
   - **Purpose**:
     - Monitor individual and team performance trends.
     - Identify employees or groups at risk of dissatisfaction and attrition.

4. **Attrition Dashboard**
   - **Metrics**: Attrition rate analysis by department, travel frequency, overtime requirements, and tenure.
   - **Visualizations**:
     - Bar chart: Attrition by department and job role.
     - Bar chart: Attrition by travel frequency and overtime requirements.
     - Line chart: Attrition trends by employee tenure.
   - **Purpose**:
     - Identify drivers of attrition across departments, job roles, and working conditions.
     - Provide actionable insights to reduce turnover and improve retention.

---

## **Results**

### **Hypothesis**
We hypothesized that:
1. Employee satisfaction metrics (e.g., job satisfaction, work-life balance) strongly influence attrition.
2. Employees in roles requiring frequent travel or overtime are more likely to leave.
3. Specific departments or roles have higher attrition rates due to job conditions or organizational factors.

### **Key Findings**
1. **Workforce Distribution**:
   - Total Employees: **1,470**.
   - Active Employees: **1,233** (83.9%).
   - Inactive Employees: **237** (16.1% attrition rate).

2. **Attrition Trends**:
   - **Departments with Highest Attrition**: Technology and Sales (attrition rate ~40%).
   - **Job Roles with Highest Attrition**: Sales Executive and Software Engineers.
   - **Impact of Travel and Overtime**:
     - Frequent travelers have an attrition rate of **30%**, higher than employees with no travel.

3. **Satisfaction Metrics**:
   - Employees with "Very Dissatisfied" ratings have a **50% attrition rate**, compared to only **10%** for "Very Satisfied" employees.
   - Work-life balance dissatisfaction contributes to increased turnover.

4. **Tenure and Attrition**:
   - Employees with **<2 years of tenure** are **20% more likely** to leave compared to those with longer tenure.

---

## **Conclusion**
This HR Analytics project provides actionable insights into Atlas Labs' workforce dynamics:
1. **Attrition Drivers**:
   - Departments and roles with high attrition rates require immediate attention, particularly Technology and Sales.
   - Dissatisfaction with work-life balance and frequent travel are significant predictors of attrition.

2. **Retention Strategies**:
   - Focus on improving job satisfaction and work-life balance through targeted HR policies.
   - Develop retention programs for early-tenure employees and frequent travelers.

3. **Workforce Optimization**:
   - Insights into workforce demographics and performance metrics support better resource allocation and diversity initiatives.

By leveraging these insights, Atlas Labs can improve employee satisfaction, reduce turnover, and enhance organizational performance.

---

## **Repository Contents**
- **Power BI File**:
  - `.pbix` file containing the dashboards and analysis.
- **Dataset**:
  - Dataset for reference.
- **README**:
  - Detailed documentation of the project, including objectives, analysis, results, and conclusions.
