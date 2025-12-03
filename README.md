1. Data Cleaning

Actions performed:

Checked for missing values

Checked for duplicated rows

Converted VisitDate to datetime

Ensured numeric columns use correct data types

 2. Feature Engineering

✔ AgeCategory

Child: < 18

Adult: 18–59

Senior: 60+


✔ BMICategory

Underweight → BMI < 18.5

Normal → 18.5–24.9

Overweight → 25–29.9

Obese → 30+


✔ HighBP

Yes → BloodPressure > 140

No → otherwise

 3. Analysis Results

🔹 Average BMI

Calculated using mean of BMI column.

🔹 Gender Distribution

Counts and percentages for Male/Female.

🔹 Percentage of Smokers

Percentage of patients who smoke vs non-smokers.

🔹 Most Common Symptom

Most frequent symptom in the dataset.

🔹 Average Blood Pressure per Chronic Disease Group

Computed using groupby to compare between groups.

🔹 Age Category With Highest Chronic Disease Cases

Shows whether adults, seniors, or children are most affected.


4. Visualizations

The project generates:

✔ Line Plot

Number of visits per day

✔ Bar Plot

Blood pressure by gender

✔ Pie Chart

Age category distribution

All charts are created using Matplotlib only.


5. Technologies Used

Python

Pandas

Matplotlib

Jupyter Notebook / .py script



6. Files Included

healthcare_data.csv

Main analysis code (.ipynb or .py)

All generated visualizations

README.md (this file)



. Summary

This project provides a complete analysis of healthcare visit data including:

Data processing

Feature engineering

Medical insights

Visual representations

