📊 Student Performance Analysis (EDA)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a student performance dataset to understand the key factors that influence academic results. The analysis explores relationships between variables such as study time, absences, parental support, extracurricular activities, and GPA.

Using Python and data visualization techniques, the project identifies meaningful patterns and insights that help explain how different factors impact student academic performance.

🎯 Objectives

The main goals of this project are:

To understand the structure and characteristics of the dataset

To analyze how different features affect student GPA

To identify correlations between variables

To visualize patterns in student performance data

To derive meaningful insights that explain academic outcomes

📂 Dataset Information

The dataset contains 999 student records with 15 features representing demographic, academic, and behavioral attributes.

Features in the Dataset
Feature	Description
StudentID	Unique identifier for each student
Age	Age of the student
Gender	Gender of the student
Ethnicity	Ethnicity category
ParentalEducation	Education level of parents
StudyTimeWeekly	Weekly study time (hours)
Absences	Number of absences
Tutoring	Whether student receives tutoring
ParentalSupport	Level of parental support
Extracurricular	Participation in extracurricular activities
Sports	Participation in sports
Music	Participation in music activities
Volunteering	Participation in volunteering
GPA	Grade Point Average
GradeClass	Academic performance category
⚙️ Technologies Used

Python

Google Colab / Jupyter Notebook

Pandas – Data manipulation

NumPy – Numerical computations

Matplotlib – Data visualization

Seaborn – Statistical visualization

🔎 Exploratory Data Analysis Steps

The following steps were performed during the EDA process:

1️⃣ Data Loading

The dataset was imported and loaded into a Pandas DataFrame.

2️⃣ Data Understanding

Checked dataset shape

Reviewed column names

Identified data types

3️⃣ Data Cleaning

Checked for missing values

Verified dataset consistency

4️⃣ Statistical Summary

Descriptive statistics were used to understand the distribution of numeric features such as:

Study time

Absences

GPA

5️⃣ Univariate Analysis

Analyzed individual feature distributions using:

Histograms

Boxplots

6️⃣ Bivariate Analysis

Explored relationships between variables such as:

Study Time vs GPA

Absences vs GPA

Gender vs GPA

7️⃣ Correlation Analysis

A correlation matrix heatmap was generated to identify relationships between variables.

📈 Key Visualizations

The project includes several visualizations to better understand the dataset:

Correlation Heatmap

Study Time vs GPA Scatter Plot

Absences vs GPA Scatter Plot

Gender vs GPA Box Plot

Feature Distribution Histograms

These visualizations help highlight patterns and relationships in the data.

💡 Key Insights

Some important insights from the analysis include:

Students with more absences tend to have lower GPAs.

Higher weekly study time slightly improves academic performance.

Parental support shows a positive relationship with GPA.

Gender does not show a significant difference in GPA distribution.

Extracurricular activities show a balanced but limited impact on GPA.

📁 Project Structure
Student-Performance-EDA
│
├── student_performance.ipynb
├── dataset.xlsx
├── README.md
🚀 How to Run the Project

Clone this repository

git clone https://github.com/yourusername/student-performance-eda.git

Open the notebook in Google Colab or Jupyter Notebook

Install required libraries

pip install pandas numpy matplotlib seaborn

Run the notebook cells step by step to reproduce the analysis.

📊 Future Improvements

Possible improvements for this project:

Build a machine learning model to predict GPA

Perform feature engineering

Apply advanced statistical analysis

Build an interactive dashboard

👨‍💻 Author

Yash Vardhan Ojha
B.Tech Information Technology
Interested in Data Analytics, Machine Learning, and Software Development
