# Employee Resignation Prediction

In this project, I worked on predicting whether an employee is likely to resign based on their attributes using various machine learning models. I compared multiple regression approaches to see which ones perform best in capturing the patterns that lead to employee attrition.

## Overview

The goal of this project was to understand and predict why employees leave a company. I used a dataset containing HR-related information like satisfaction levels, number of projects, average working hours, promotions, and salary levels. I experimented with a range of regression models to see how well each one could predict employee resignation.

## Dataset

The dataset contains the following features:

| Feature                  | Description                                      |
|--------------------------|--------------------------------------------------|
| satisfaction_level       | Employee satisfaction score                     |
| last_evaluation          | Last performance evaluation score               |
| number_project           | Number of projects participated in              |
| average_montly_hours     | Average monthly working hours                   |
| time_spend_company       | Number of years at the company                  |
| Work_accident            | Whether the employee had a work accident        |
| promotion_last_5years    | Whether they got a promotion in the last 5 years|
| sales                    | Department name                                 |
| salary                   | Level of salary (low, medium, high)             |
| left                     | Target variable: 1 if left, 0 otherwise         |

## What I Did

- Explored the dataset and performed EDA to identify key trends
- Preprocessed the data by encoding categorical features and checking for missing values
- Trained and evaluated the following regression models:

### Models I Used (from simple to advanced):

1. Multiple Linear Regression  
2. Decision Tree Regressor  
3. Random Forest Regressor  
4. CatBoost Regressor  
5. XGBoost Regressor  

## Evaluation Metrics

To evaluate how well each model performed, I used the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

After training all the models, I found that Random Forest, XGBoost, and CatBoost gave similar and much better results compared to Linear Regression and Decision Tree models. These advanced, tree-based models were more accurate and better at capturing the complex relationships in the data.

## Key Insights

- Employees with low satisfaction levels and high average monthly hours are more likely to leave.
- Number of projects and evaluation scores also play a role in attrition.
- Advanced ensemble models like XGBoost and CatBoost not only performed well but also provided meaningful feature importance.

## File Structure

