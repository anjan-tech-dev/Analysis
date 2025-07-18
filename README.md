# 📊 Student Performance Analysis Using SQL & Python

This project analyzes a student performance dataset using **Python (Pandas, Matplotlib, Seaborn)** and **SQL (MySQL)**. The goal is to extract actionable insights that help understand the key factors influencing academic performance such as study hours, sleep duration, practice habits, and extracurricular involvement.

---

## 📁 Dataset Features

| Column                                           | Description                                        |
|---------------------------                       |----------------------------------------------------|
| `Student_ID`                                     | Unique identifier for each student                |
| `Sleep Hours`                                    | Average hours of sleep per night                  |
| `Hours Studied`                                  | Daily average study duration (in hours)           |
| `Performance Index`                              | A score out of 100 measuring academic performance |
| `Sample Question Papers Practiced`               | No. of practice papers solved                     |
| `Extracurricular Activities`                     | Participation in extra activities (Yes/No)       |

---

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Performed in Python:
Data Cleaning: Checked for null values, data types, and duplicates.
Statistical Summary: Used .describe() and .info() for dataset overview.
Visualizations & Analysis:
Histograms for numerical features(Univariate Plots).
Various plots for bivariate analysis.

## Insights from SQL Queries
High Performers have an average study time of 7 hours.
8 hour sleep is giving highest performance.
Students who did not score good early are also less likely to score later.
Students involved in extracurricular activities have slightly less performance index.
Best combination is 7 hours sleep and 9 hours study


## Insights from EDA
Data is mostly clean,no duplicate or null values.
More study hours lead to more performance.
The more the previous score,more is the performance index.
Sleep of 8-9 hours lead to more performance.

