# HR Analytics & Employee Attrition Dashboard

## Project Overview
An interactive HR Analytics dashboard developed using Power BI to analyze employee demographics, workforce distribution, and employee attrition. The project helps explore workforce patterns and understand factors associated with employee attrition through interactive visualizations.

## Project Objectives
- Analyze employee attrition across different departments and job roles.
- Explore workforce demographics such as age, gender, and education.
- Examine attrition patterns related to job satisfaction, work-life balance, and overtime.
- Present key HR metrics through an interactive dashboard.

## Tools & Technologies
- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculated columns
- **IBM HR Analytics Dataset** – Data source

## Dashboard Pages

### 1. HR Executive Overview
Provides an overview of key HR metrics, including total employees, active employees, attrition count, attrition rate, average monthly income, and average tenure.

### 2. Employee Attrition Analysis
Explores attrition patterns based on job satisfaction, environment satisfaction, work-life balance, business travel, tenure, and salary groups.

### 3. Workforce Demographics & Performance
Analyzes workforce distribution by department, education level, job role, age group, and gender, along with job satisfaction and monthly income metrics.

## Data Preparation
- Removed unnecessary constant columns.
- Checked for missing values and duplicate employee records.
- Created dimension tables for Department, Job Role, and Education.
- Established relationships between dimension tables and the employee fact table.
- Created calculated columns to categorize employees by age, tenure, and salary.

## Key Metrics
- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate
- Average Age
- Average Tenure
- Average Monthly Income
- Average Job Satisfaction
- Overtime Employees

## Interactive Features
- Department, Gender, and Job Role slicers.
- Synchronized filters across all three dashboard pages.
- Interactive charts and KPI cards.
- Page navigation for easy exploration.

## Project Files
- `HR_Analytics_Employee_Attrition_Dashboard.pbix` – Interactive Power BI dashboard.
- `HR_Analytics_Employee_Attrition_Report.pdf` – PDF version of the dashboard.

## Dataset Source
IBM HR Analytics Employee Attrition & Performance Dataset  
[Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Note
This project uses a sample IBM HR Analytics dataset for analytical and educational purposes. The findings describe patterns in the provided dataset and should not be interpreted as causal conclusions or representative of every organization's workforce.

