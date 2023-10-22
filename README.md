# My-Data-Science-Project
# Human Resources Data Analysis

This repository contains a Python script for analyzing Human Resources data using the pandas library. The dataset is provided as a CSV file, and the script answers various questions and visualizes the data to gain insights into employee information, performance, and more.

## Table of Contents
1. [Pandas Questions](#pandas-questions)
2. [Exploratory Data Analysis (EDA) and Data Visualization](#eda-and-data-visualization)
3. [Machine Learning Model](#machine-learning-model)
4. [Insights](#insights)

## Pandas Questions
The script answers the following questions using the pandas library:

1. What is the minimum, median, max, and average salary for employees by Married Description and Gender?
2. What are the top-5 reasons for termination?
3. What is the highest number of employees by Recruitment Source that 'Exceeds' the Performance Score?
4. How many managers are there in each department?
5. What is the Termination Ratio by Gender?

## EDA and Data Visualization
The script also provides data visualization to gain insights into the dataset. It includes visualizations like bar charts, scatter plots, and pie charts to explore the data visually. Some of the visualizations include:

1. Ratio of termination by Gender
2. Scatter plot between Salary and Engagement Survey
3. Bar chart to count termination by department
4. Pie chart to show the percentage of terminated employees by Position
5. Boxplot of Salary by Marital Description, distinguished by Termd
6. Pairplot for columns 'Salary', 'EngagementSurvey', 'EmpSatisfaction', 'Absences' with color-coded 'Termd'

## Machine Learning Model
A machine learning model is created to predict the 'Termd' status. The script covers the following steps:
1. Creating a new feature 'Age' from the 'DOB' column.
2. Applying MinMaxScaler to the 'Salary' feature.
3. Changing all object data types to category.
4. Using Label Encoder for 'RecruitmentSource' and 'PerformanceScore'.
5. Splitting the data into a training and testing set (80:20).
6. Building a Logistic Regression model to predict 'Termd' and evaluating the model's accuracy, precision, and recall.

## Insights
The script also answers two important questions:
1. Is there any relationship between who a person works for (their manager) and their performance score?
2. What are the best recruiting sources if we want to ensure a low ratio of termination?

The code provides insights into these questions by visualizing the relationship between managers and performance scores and by examining the impact of recruitment sources on termination rates.

Feel free to explore the Python script to learn more about the dataset and gain valuable insights from the HR data.

## How to Use
To use the Python script, make sure you have the required libraries installed. You can run the script in your preferred Python environment. The script is well-documented, and you can modify it to suit your specific needs.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
