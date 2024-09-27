# Student Performance Prediction: A Case Study of Portuguese Language Class

This project analyzes the performance of students in secondary education at two schools in Alentejo, Portugal, during the 2005-2006 school year. The goal is to predict the final grade (G3) in the Portuguese language course based on student grades, demographic, social, and school-related features.

## Dataset:
The dataset used in this project is publicly available at https://archive.ics.uci.edu/ml/datasets/Student+Performance. It includes information on students' performance in the Portuguese language course.

## Project Objective

The objective of this project is to create a model that predicts the final grades (G3) of students using various features. These features include students' study habits, alcohol consumption, absences, and first and second period grades (G1, G2).

## Methodology

1. T-Tests and Regression Analysis were conducted to evaluate the impact of various predictors on students' final grades.
2. Model Selection was performed using regsubsets and AIC to find the best predictors while avoiding overfitting.
3. Residual Analysis was conducted to examine the fit of the model and assess potential issues with explanatory variables like absences.

Model Selection: The final model was chosen for its balance between a high adjusted R-squared value and the lowest Mallow’s Cp and AIC. The selected model uses 5 of the 33 available predictors, reducing complexity.

## Key Findings

After a thorough model selection process, the best predictors for G3 (final grade) were found to be: Study time, Alcohol consumption on workdays, Absences, First period grade (G1), Second period grade (G2)

    