## Introduction
This data jobs salary dashboard was created to help job seekers investigate salaries for their desired jobs and ensure they are being adequately compensated.

The data provides a foundation in analyzing data using this powerful tool. The data contains detailed information on job titles, salaries, locations, and essential skills that are presented here.

## Excel Skills Used
The following Excel skills were utilized for analysis:
📉 Charts
🧮 Formulas and Functions
❎ Data Validation

##Data Jobs Dataset
The dataset used for this project contains real-world data science job information from 2023. The dataset is available via my Excel course, 
which provides a foundation for analyzing data using Excel. It includes detailed information on:
👨‍💼 Job titles
💰 Salaries
📍 Locations
🛠️ Skills

## Dashboard Build:
📉 Charts
📊 Data Science Job Salaries - Bar Chart
<img width="1309" height="425" alt="dashboard pic" src="https://github.com/user-attachments/assets/40f05386-4dbe-407f-915f-19cb60823399" />


## 1.Salary Dashboard Chart - Bar Chart:
🛠️ Excel Features: Utilized bar chart feature (with formatted salary values) and optimized layout for clarity.
🎨 Design Choice: Horizontal bar chart for visual comparison of median salaries.
📉 Data Organization: Sorted job titles by descending salary for improved readability.
💡 Insights Gained: This enables quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles.
🗺️ Country Median Salaries - Map Chart

## 2.Salary_Dashboard_Chart- Map:
🛠️ Excel Features: Utilized Excel's map chart feature to plot median salaries globally.
🎨 Design Choice: Color-coded map to visually differentiate salary levels across regions.
📊 Data Representation: Plotted median salary for each country with available data.
👁️ Visual Enhancement: Improved readability and immediate understanding of geographic salary trends.
💡 Insights Gained: Enables quick grasp of global salary disparities and highlights high/low salary regions.

## 🧮 Formulas and Functions:
💰 Median Salary by Job Titles:
=MEDIAN(
IF(
    (jobs[job_title_short]=A2)*
    (jobs[job_country]=country)*
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type])))*
    (jobs[salary_year_avg]<>0),
    jobs[salary_year_avg]
)
)

🔍 Multi-Criteria Filtering: Checks job title, country, schedule type, and excludes blank salaries.
📊 Array Formula: Utilizes MEDIAN() function with nested IF() statement to analyze an array.
🎯 Tailored Insights: Provides specific salary information for job titles, regions, and schedule types.
🔢 Formula Purpose: This formula populates the table below, returning the median salary based on job title, country, and type specified.
<img width="1246" height="350" alt="Pivot Chart" src="https://github.com/user-attachments/assets/2b406cd3-5c4f-450d-9774-9ddfad91bf88" />

## Conclusion:
I created this dashboard to showcase insights into salary trends across various data-related job titles. Utilizing data from my Excel course,
this dashboard allows users to make informed decisions about their career paths. Exploring the functionalities to understand how location and job type influence salaries.
