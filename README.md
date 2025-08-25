📊 Heart Disease Analysis Dashboard (Power BI)
📌 Overview

This project is a Power BI dashboard built to analyze a heart disease dataset.
It provides key insights into patient demographics, cholesterol levels, chest pain types, and disease occurrence.

The dashboard helps answer questions such as:

How many patients have heart disease vs. no disease?

How does gender and age affect heart disease prevalence?

Which chest pain type is most common among patients with disease?

What is the relationship between cholesterol and age?

🗂️ Dataset

Rows: 303 patients

Columns: age, sex, cp (chest pain), chol, thalach (max heart rate), target, etc.

Key Columns

age → Patient age

sex → Gender (0 = Female, 1 = Male)

cp → Chest Pain Type

0 = Typical Angina

1 = Atypical Angina

2 = Non-anginal Pain

3 = Asymptomatic

target → Disease Status (0 = No Disease, 1 = Disease)

📈 Dashboard Features

KPI Cards → Total Patients, Patients with Disease, Patients without Disease

Bar Charts → Gender distribution by Disease

Histogram → Age distribution of patients

Pie Chart → Cholesterol breakdown by Gender

Scatter Plot → Age vs Max Heart Rate by Disease status

Stacked Bar → Chest Pain Type by Disease

🔧 Tools Used

Power BI Desktop → Data cleaning, visualization, dashboard design

DAX → Custom measures (e.g., Patients with Disease, Patients without Disease)

GitHub → Project sharing

🚀 How to Use

Clone or download this repository.

git clone https://github.com/your-username/heart-disease-powerbi.git


Open Heart_Disease_Dashboard.pbix in Power BI Desktop.

Explore the visuals and interact with filters.


📌 Insights

Males are more likely to have heart disease than females.

Most patients fall in the 50–60 age group.

Typical Angina and Non-anginal Pain are the most common chest pain types among diseased patients.

Higher cholesterol is often linked with disease cases.

✨ Future Improvements

Add slicers for interactive filtering (Age groups, Gender).

Add a line chart: Cholesterol vs Age (overlay by Disease).

Add predictive analysis using Machine Learning models.
