# STUDENT-DATA-ANALYSIS-SC-
# Student Performance Analysis using Machine Learning & Power BI

This project is part of an internship at StableCode, focusing on analyzing student academic performance using machine learning and visualizing insights through Power BI.

# Project Structure

- `SDP ANALYSIS.ipynb`: Jupyter Notebook for data preprocessing, analysis, and ML model development (Pass/Fail prediction).
- `StudentsPerformance.csv`: Dataset with student scores and background information.
- `student marks report.pbix`: Power BI dashboard to visualize performance trends.
- `README.md`: Project summary and usage.
- `student_dashboard.pptx`: Presentation slides.

# Dataset

Source: [Kaggle - Students Performance Dataset]

Features:
- Gender, race/ethnicity, parental level of education
- Lunch type, test preparation course
- Math, reading, and writing scores

# Objective

- Predict student result (pass/fail) using ML based on their scores.
- Visualize academic performance trends using Power BI.

# Technologies Used

- Python, Pandas, Scikit-learn
- Random Forest Classifier
- Power BI for dashboard creation
- Jupyter Notebook

# ML Model

- Label Encoding for categorical data
- Created 'average' score column
- Defined pass/fail based on average score ≥ 50
- Used Random Forest for prediction

# Power BI Dashboard

Visuals:
- Bar Chart: Average scores by gender
- Pie Chart: Test preparation course completion
- Stacked Column Chart: Scores by parental education
- Slicers: Gender, Lunch Type, Test Prep

# How to Run

1. Open `SDP ANALYSIS.ipynb` in Jupyter Notebook
2. Run all cells to preprocess data and train the model
3. Open `student marks report.pbix` in Power BI Desktop
4. Load the `processed_student_data.csv` if needed and explore the dashboard

# Outcome

- Achieved accurate prediction of pass/fail status
- Identified patterns in scores by gender, education, and test prep
- Delivered a clean, interactive dashboard for insights

