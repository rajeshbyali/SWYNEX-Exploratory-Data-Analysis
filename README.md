# SWYNEX – Task 2: Exploratory Data Analysis

## Project Objective
Perform exploratory data analysis on the cleaned dataset from Task 1, calculate important statistics, identify trends/patterns/anomalies, create charts, and document at least five useful insights.

## Dataset
This project directly uses the **cleaned HR employee dataset produced in SWYNEX Task 1**.

Rows: **500**  
Columns: **15 analytical columns** (plus EDA helper fields created during analysis)

> Important: The Task 1 dataset is a controlled demonstration dataset based on an HR analytics benchmark. The observations and insights below describe this project sample and should not be treated as real-world IBM workforce statistics.

## Tools Used
- Python
- Pandas
- Matplotlib
- Excel
- GitHub

## EDA Performed
1. Descriptive statistics
2. Attrition distribution
3. Attrition by department
4. Attrition by overtime status
5. Attrition by business travel
6. Attrition by job role
7. Attrition by age group
8. Monthly income comparison
9. Tenure comparison
10. Job satisfaction and work-life balance analysis
11. Numeric correlation analysis
12. Visual anomaly/pattern review

## Key Results
- Overall attrition rate: **13.4%**
- Overtime attrition: **22.4%**
- Non-overtime attrition: **9.5%**
- Highest department attrition: **Human Resources (25.0%)**
- Highest job-role attrition: **Human Resources (37.5%)**

## Five+ Useful Insights
1. The cleaned sample contains 500 employees, with 67 attrition cases. The overall attrition rate is 13.4%.
2. Overtime is the clearest segmentation in this sample: employees working overtime have a 22.4% attrition rate versus 9.5% for employees without overtime.
3. Human Resources has the highest department-level attrition rate at 25.0%, compared with 17.4% across the three departments.
4. The Human Resources role has the highest observed role-level attrition rate (37.5%), but it represents only 8 employees, so the rate should be interpreted cautiously.
5. The 26-35 age group has the highest attrition rate at 16.3% in this sample.
6. Employees who left had a lower average tenure (5.33 years) than employees who stayed (6.42 years), a difference of 1.09 years.
7. Median monthly income is very similar for employees who stayed (6,514) and those who left (6,469), suggesting income alone is not a strong separator in this sample.
8. Work-life balance level 4 shows an 8.8% attrition rate versus 16.1% at level 2, indicating a possible relationship worth validating with a larger dataset.

## Important Interpretation Note
EDA shows associations and patterns; it does not prove causation. Small groups, especially individual job roles, can produce unstable percentages. These findings should be validated with a larger dataset and statistical/model-based analysis before making business decisions.

## Repository Structure
```text
SWYNEX-Exploratory-Data-Analysis/
├── README.md
├── data/
│   └── cleaned_hr_dataset.csv
├── charts/
│   ├── 01_attrition_distribution.png
│   ├── 02_overtime_attrition.png
│   ├── 03_department_attrition.png
│   ├── 04_jobrole_attrition.png
│   ├── 05_agegroup_attrition.png
│   ├── 06_income_distribution.png
│   └── 07_tenure_attrition.png
├── docs/
│   ├── SWYNEX_Task2_EDA_Analysis.xlsx
│   ├── SWYNEX_Task2_EDA_Report.docx
│   ├── SWYNEX_Task2_EDA_Report.pdf
│   └── LinkedIn_Post.md
└── scripts/
    ├── eda_analysis.py
    └── requirements.txt
```
