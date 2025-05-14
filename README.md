# Data-Cleaning-Analysis-in-Excel

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Dashboard](#dashboard)
- [Tools](#tools)
- [Data Cleaning/Preparation](#datacleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [ Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)

### Project Overview
The project aimed to explore employee performance and productivity, providing insights into how well the employees are satisfied with their jobs and if the level of job satisfaction impact their output at work.

### Data Source
The primary dataset used for this analysis is the "employee_performance_and_productivity_data.csv" file, containing performance score, employee satisfaction score, work_hours_per_week, overtime_hours, project handled.

### Dashboard
![Performance Dashboard](https://github.com/Funke-Shittu/Data-Cleaning-and-Analysis-in-Excel/blob/main/Performance_report.png)


### Tools
- Power Query -Data Cleaning
- Excel - Analysis [Download Here](https://github.com/Funke-Shittu/Data-Cleaning-and-Analysis-in-Excel/blob/main/Employee_Performance_Productivity%20Data.xlsx)

### Data Cleaning/Preparation

At the preparation phase, the following tasks was performed;

1. Data extraction and inspection
2. Handling inconsistent data type
3. Data formatting

### Exploratory Data Analysis 
EDA involved exploring the employee and productivity data to give answers to the following question;
1.Is there a productivity across depertments?
2. Does Education_level & cummulative work_hours impact productivity?
3. Correlation between performance and Years_at_Company?

### Data Analysis
Some formulas used include

`Productivity_score =
projects_handled/work_hours_per_week*100`

`Employee Satisfaction =
IFS(S3>=4,"Very Satisfied",S3>=3,"Satisfied",S3<3,"Not Satisfied")`

### Findings
1. 49.96% of employee are not satisfied with their job.
2. There is no correlation between employee performance, Years_at_Company and work_hours_per_week.

### Recommendations
- Consider why PhD holders and other degree holders do not perform as high as BSc. holders.
- Encourage best practises from leadership to improve employee satisfaction.
