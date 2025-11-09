# HR Analytics Dashboard (Tableau)
# Project Overview

The HR Analytics Dashboard provides an in-depth analysis of employee attrition, department performance, and workforce demographics.
It enables HR managers to identify key areas impacting employee retention and job satisfaction, helping organizations make data-driven HR decisions.

# Objectives

Analyze the overall attrition rate and identify high-risk employee segments.

Understand department-wise and education-wise attrition trends.

Visualize gender and age distribution in attrition.

Measure job satisfaction across different job roles.

Provide actionable insights to improve employee retention strategies.

# Dataset Information

Total Employees: 1,470
Active Employees: 1,233
Attrition Count: 237
Average Age: 37 years

Key Columns:

Column Name	Description
Employee ID	Unique employee identifier
Age	Employee’s age
Department	HR / R&D / Sales
Education Field	Employee’s education background
Gender	Male / Female
Job Role	Role in the company
Job Satisfaction	Satisfaction score (1–4)
Attrition	Yes / No
Years at Company	Duration of service

Data Source: Public HR dataset (inspired by IBM HR Analytics Attrition dataset or Kaggle HR dataset).

📸 Dashboard Preview

🧠 Key Insights
🔹 Overview Metrics

Employee Count: 1,470

Attrition Rate: 16%

Average Age: 37

Active Employees: 1,233

🔹 Department-wise Attrition

R&D: 56%

Sales: 39%

HR: 5%

🔹 Education Field-wise Attrition

Highest in Life Sciences (89) and Medical (63) fields.

🔹 Gender-based Attrition

Male: 150 attritions

Female: 87 attritions

🔹 Age-based Analysis

Most attrition seen among 30–35 year-olds.

🔹 Job Satisfaction Ratings

Research Scientist and Sales Executive have mixed satisfaction levels.

🛠️ Tools Used

Tableau Desktop / Tableau Public – Data visualization and dashboard creation

Excel / CSV – Data storage and cleaning

Power Query / Excel Functions – Data preprocessing

🚀 How to Open the Project
Option 1: Open with Tableau Desktop

Clone or download this repository:

git clone https://github.com/santhosh02-07/HR-Analytics-Dashboard.git


Open HR_Analytics_Dashboard.twb (or .twbx) in Tableau Desktop.

If prompted, connect the dataset file:

Dataset: data/HR_Data.csv

Explore filters and dashboards interactively.

Option 2: View Online

If published on Tableau Public, include your link here:

🔗 View the Dashboard on Tableau Public

📈 Summary of Insights

The R&D Department shows the highest attrition rate.

Employees aged 30–35 are most likely to leave.

Life Sciences and Medical graduates show higher turnover.

Targeting job satisfaction improvements in Sales Executives and Laboratory Technicians could reduce attrition.

# Recommended Repository Structure

HR-Analytics-Dashboard/
│
├── data/
│   └── HR_Data.csv
│
├── dashboard/
│   └── HR_Analytics_Dashboard.twbx
│
├── images/
│   └── dashboard_preview.png
│
├── README.md
└── LICENSE (optional)
