# Predicting Used Car Prices in Saudi Arabia

## Capstone Project by Nurmaryo Anggito

## Introduction
The used car market in Saudi Arabia is dynamic and influenced by various factors such as the type of car, region, brand, transmission type, origin, additional options, manufacturing year, engine size, mileage, and negotiation. Sellers and buyers often face challenges in determining a fair and competitive price for used cars.
## Problems
The absence of a reliable pricing model for used cars in Saudi Arabia hinders the ability of sellers to set competitive prices and buyers to make informed purchasing decisions. Traditional methods may not consider various factors affecting car prices, leading to inaccuracies in pricing and potential financial losses for both sellers and buyers.
## Goals
1. Develop a machine learning model capable of predicting the selling price of used cars with high accuracy.
2. Explore and evaluate several regression models, including traditional techniques and ensemble methods.
3. Use metrics such as Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE) to assess model performance.

## Project Scope
This project focuses on creating and evaluating regression models, including traditional techniques and ensemble methods. Evaluation will be based on performance metrics such as MAPE, RMSE, and MAE.

The success of the project will be measured based on the developed model's ability to predict used car prices with low MAPE, RMSE, and MAE. A successful model will provide a valuable tool for both sellers and buyers in the Saudi Arabian used car market.
## Scoring Metrics

1. Mean Absolute Percentage Error (MAPE):
- Usage: Measures the accuracy of predictions in the form of a percentage error relative to the actual value.
- Function: Provides an indication of how much the prediction error is in percentage terms relative to the actual value.
- Comparison: Smaller MAPE values indicate higher accuracy.

2. Root Mean Squared Error (RMSE):
- Usage: Measures how spread out the prediction errors are in the actual values.
- Function: Indicates the extent of the difference between predicted and actual values.
- Comparison: Smaller RMSE values indicate higher accuracy.

3. Mean Absolute Error (MAE):
- Usage: Measures the average absolute error between predicted and actual values.
- Function: Gives an overview of how close predictions are to the actual values.
- Comparison: Smaller MAE values indicate higher accuracy.
## Model
The following regression models will be used in the project:

- Linear Regression
- Huber Regressor
- RANSAC Regressor
- TheilSen Regressor
- Decision Tree Regressor
- KNeighbors Regressor
- RandomForest Regressor
- AdaBoost Regressor
- CatBoost Regressor
- Support Vector Regressor (SVR)
## Data Definition

COLUMN DESCRIPTION
| Column        | Data Type | Description                                       |
|---------------|-----------|---------------------------------------------------|
| <span style="color:yellow">Type</span>| object    | Type of used car.                                 |
| <span style="color:yellow">Region</span>        | object    | The region in which the used car was offered.     |
| <span style="color:yellow">Make</span>          | object    | Company name (manufacturer) of the used car.      |
| <span style="color:yellow">Gear_Type</span>     | object    | Gear type/size of the used car.                   |
| <span style="color:yellow">Origin</span>        | object    | Origin of the used car.                           |
| <span style="color:yellow">Options</span>       | object    | Options available for the used car (Mungkin jenis aksesoris atau tambahan).               |
| <span style="color:yellow">Year</span>          | int64     | Manufacturing year of the used car.               |
| <span style="color:yellow">Engine_Size</span>   | float64   | Engine size of the used car.                      |
| <span style="color:yellow">Mileage</span>       | int64     | Mileage of the used car.                          |
| Negotiable    | bool      | True if the price is 0 (negotiable), otherwise False. |
| <span style="color:Green">Price</span>         | int64     | Price of the used car.     |

Notes:
- <span style="color:yellow">Kuning</span> : Features
- <span style="color:green">Hijau</span> : Target

## Methodology
1. Data Loading and Exploration:
- Load the dataset and explore its structure, features, and distributions.
- Check for missing values, outliers, and data types.
- Visualize the distribution of the target variable (Price) and key features.

2. Data Cleaning and Preprocessing:
- Handle missing values, outliers, and data type conversions.
- Encode categorical variables and handle any necessary feature engineering.
- Normalize or scale numerical variables.

3. Exploratory Data Analysis (EDA):
- Analyze relationships between features and the target variable.
- Identify patterns, correlations, and potential insights.

4. Feature Engineering:
- Evaluate and transform numerical and categorical variables.

5. Model Selection and Evaluation:
- Implement various regression models (Linear Regression, Decision Tree, Random Forest, etc.).
- Use cross-validation to evaluate and compare model performance.
- Tune hyperparameters using GridSearchCV.

6. Model Interpretation:
- Interpret model coefficients or feature importances.
- Analyze the impact of different features on the predicted prices.

7. Model Deployment and Documentation:
- Choose the final model based on evaluation metrics.
- Document the model, its features, and instructions for use.
- Provide insights and recommendations for users.
## Conclusion
This capstone project aims to develop a robust machine learning model for predicting used car prices in Saudi Arabia. The comprehensive approach includes data exploration, cleaning, preprocessing, feature engineering, model selection, evaluation, interpretation, and documentation. The success of the project will be measured by the model's accuracy in predicting prices and its usability in the Saudi Arabian used car market.
