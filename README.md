# HR-Data-Analysis-Project
This project analyzes employee data to uncover patterns in attrition, job satisfaction, salary distribution, and other critical HR metrics. Using Power BI, I designed an interactive dashboard that helps HR teams gain insights into employee trends and improve decision-making.  The dashboard features dynamic visualizations, slicers for filtering, and calculated metrics to identify key factors driving employee attrition and satisfaction.
# Dataset
Source: Hypothetical HR Data collected from company records and surveys.
File: HR_Analytics_Dataset.xlsx

# Key Fields in the Dataset:

Employee ID
Department
Job Role
Education
Age
Monthly Salary
Attrition (Yes/No)
Job Satisfaction (Scale: 1–5)
Years at Company
Employee Count
Attrition Count

![image](https://github.com/user-attachments/assets/71f34155-9c68-4dd9-bace-8d7293c75289)

# Key Features of the Dashboard
1. Employee Count Overview
Visual: Card
Description: Displays the total number of employees in the organization.
Slicers Used: Department, Job Role
2. Attrition Overview
Visual: Card
Description: Shows the total number of employees who have left the organization.
Slicers Used: Department, Job Role
3. Attrition Rate
Visual: Card
Description: Calculates the percentage of employees who have left the organization.
Measure Formula:
DAX
Copy code
Attrition Rate = DIVIDE(SUM(HR_Analytics[AttritionCount]), SUM(HR_Analytics[EmployeeCount]))
4. Attrition by DepartmentVisual: Clustered Bar Chart
Description: Compares attrition rates across different departments.
Fields:
Axis: Department
Values: Attrition Count
5. Salary Distribution
Visual: Stacked Column Chart
Description: Visualizes the distribution of salaries across different job roles.
Fields:
Axis: Job Role
Values: Monthly Salary
6. Attrition by Education
Visual: Donut Chart
Description: Shows how attrition varies across educational backgrounds.
Fields:
Values: Attrition Count
Legend: Education
7. Job Satisfaction Analysis
Visual: Stacked Bar Chart
Description: Compares job satisfaction scores across job roles.
Fields:
Axis: Job Role
Values: Job Satisfaction Score
8. Attrition by Age Group
Visual: Line Chart
Description: Highlights attrition trends among different age groups.
Fields:
Axis: Age Group
Values: Attrition Count
Insights and Analysis
Employee Attrition:

Certain departments exhibit higher attrition rates, indicating potential issues with job satisfaction or workload.
Employees in specific job roles or with lower salaries are more likely to leave.
Job Satisfaction Trends:

Higher job satisfaction scores correlate with lower attrition rates.
Employees in technical roles tend to report higher satisfaction scores compared to administrative roles.
Salary Distribution:

Attrition rates are higher among employees in the lower salary brackets.
There’s a noticeable gap in salaries across job roles, highlighting potential inequities.
Age Group Analysis:

Younger employees (age 20–30) have a higher attrition rate, possibly due to career mobility.
Employees aged 40+ show greater stability and lower attrition rates.
Educational Impact:

Employees with technical degrees exhibit the lowest attrition rates, emphasizing the need to recruit and retain technical talent.

# How to Use the Dashboard
Open the Power BI File:

Download and open the HR_Analytics.pbix file in Power BI Desktop.
Interact with the Visuals:

Use slicers (e.g., Department, Job Role, Education) to filter the data and focus on specific segments.
Explore Insights:

Analyze attrition trends, salary distributions, and job satisfaction scores by adjusting the filters.
Export or Share:

Export visuals or share the Power BI file to collaborate with stakeholders.

# 5. Technical Details
Power BI Version: 2.136.1478.0
Data Model: Structured relational data imported from an Excel file.
Measures and Calculations:
Attrition Rate
Job Satisfaction Analysis
Salary Distribution Metrics
Transformations:
Cleaned and transformed the dataset to remove inconsistencies and prepare for analysis.

# Limitations
Data Accuracy:

The analysis depends on the quality of the dataset. Regular updates are essential for accurate insights.
Dynamic Data:

Attrition data may change frequently; ensure the dataset is refreshed periodically.
Privacy Concerns:

All personal identifiers have been anonymized to protect employee privacy.
# Contact
Name: Janhavi Hiremath
Email: swamijanhavi287@gmail.com


