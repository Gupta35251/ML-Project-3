Wine Quality Prediction using XGBRegressor
📌 Project Title

Predicting Wine Quality using XGBoost Regression
📚 Project Overview

This project focuses on predicting the quality of wine based on its chemical properties using the XGBRegressor model. The wine quality is treated as a continuous value, making this a regression task.
🧠 Machine Learning Workflow
1. Problem Statement

To predict the quality score of wine (0–10) based on features like acidity, sugar, alcohol content, etc., using the XGBoost regression model.
2. Dataset Information

    Source: UCI Wine Quality Dataset

    Type: CSV file

    Features (Examples):

        Fixed acidity

        Volatile acidity

        Citric acid

        Residual sugar

        Chlorides

        pH

        Alcohol

        Sulphates

        etc.

    Target: quality (numeric score)

3. Preprocessing Steps

    Checked and handled missing values

    Scaled/normalized features if needed

    Split data into training and testing sets

4. Model Used

    ✅ XGBRegressor from the XGBoost library

    Model trained with default or tuned hyperparameters

    Known for its high performance in regression tasks

5. Evaluation Metrics

    R² Score: Measures how well the model fits the data

    Mean Absolute Error (MAE): Average prediction error

    Mean Squared Error (MSE): Penalizes larger errors more

   🛠️ Tools & Libraries

    Language: Python

    Environment: Jupyter Notebook

    Libraries:

        pandas, numpy – Data handling

        matplotlib, seaborn – Visualization

        xgboost – Model

        sklearn – Metrics
