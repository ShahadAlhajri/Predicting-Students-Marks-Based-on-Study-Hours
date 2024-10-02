# Predicting Students' Marks Based on Study Hours



## Overview



This project implements the Simple Linear Regression algorithm to predict students' final exam marks based on the number of hours they study. By analyzing the relationship between study hours and academic performance, the project aims to provide insights into how study time influences exam results.



## Objectives



- Develop a Linear Regression model to predict students' final exam marks based on study hours.

- Assess the model's accuracy using relevant performance metrics.

- Provide insights into the relationship between study time and academic performance.



## Dataset



The dataset used in this project consists of 179 instances, each representing a student. It includes two key attributes:



- **Marks:** The marks obtained by students in a specific subject or exam.

- **Study Time:** The amount of time students dedicate to studying.



## Model


### Simple Linear Regression



Simple Linear Regression is a supervised learning algorithm that establishes a linear relationship between an independent variable (study time) and a dependent variable (marks). The regression model predicts the value of the dependent variable based on the independent variable.






## Model Development



1. **Data Preprocessing:**

   - Load the dataset and clean it by removing missing values and duplicates.

   - Remove outliers based on predefined criteria.



2. **Model Training:**

   - Split the dataset into features (X) and target variable (Y).

   - Create and train the Linear Regression model on the training data.



3. **Prediction and Visualization:**

   - Make predictions on the test set.

   - Visualize the training and test sets along with the regression line.



4. **Model Evaluation:**

   - Measure performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).



## Results



The model achieved a high R-squared value of 0.95, indicating that 95% of the variance in final exam marks can be explained by study hours. The Mean Absolute Error (MAE) was 2.24, suggesting that the model's predictions are generally accurate.



## Conclusion



The analysis demonstrates a strong relationship between study time and exam marks. The Simple Linear Regression model provides reliable predictions of students' academic performance based on their study habits. Future work may explore more complex models or additional features to further enhance prediction accuracy.
