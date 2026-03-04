Student Performance – Data Analysis & Visualization This project performs exploratory data analysis (EDA) on a student performance dataset containing 2,392 students and 15 features, including GPA, absences, study time, parental support, tutoring, and extracurricular activities.

Objectives

Understand the factors that influence student GPA and grade class Clean and validate the raw dataset for analysis Visualize key patterns and relationships using Python

Tools & Libraries Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

What's Covered Data Cleaning

Fixed incorrect data types Decoded encoded categorical columns Validated GPA vs Grade Class consistency Handled precision issues on float columns Domain/range validation for all features

Visualizations (12 Charts)

Grade class distribution GPA by parental support level Study time vs grade class Absences vs grade class Tutoring impact on GPA Age distribution Activity participation impact Feature correlation with GPA GPA distribution (KDE + Histogram) Absences vs GPA scatter plot Full correlation heatmap GPA by gender

Key Findings

Absences is the strongest predictor of GPA with a correlation of r = -0.919 Students with tutoring score on average 16% higher GPA Higher parental support consistently leads to better GPA (1.54 → 2.19) Students involved in extracurricular activities perform slightly better 50.6% of students fall in Grade F, only 4.5% achieve Grade A

Repository Structure ├── Student_performance_data__.csv # Raw dataset ├── Student_performance_cleaned.csv # Cleaned dataset ├── data_cleaning.ipynb # Data cleaning notebook ├── visualizations.ipynb # EDA & visualization notebook └── README.md

How to Run bashpip install pandas matplotlib seaborn numpy jupyter notebook Open either notebook and run cells from top to bottom.

Dataset contains 2,392 student records with features spanning demographics, study habits, family background, and academic performance.
