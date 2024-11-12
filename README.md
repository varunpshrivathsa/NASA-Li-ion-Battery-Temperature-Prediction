# NASA-Li-ion-Battery-Temperature-Prediction LINEAR REGRESSION
Uses linear regression to predict Li-ion battery temperature from operational data, supporting thermal management, safety, and performance optimization. Achieved MAE, MSE, and R² of 0.95 in evaluation.

Overview
This project predicts Li-ion battery temperature based on operational parameters (voltage, current, time, capacity) using a linear regression model. Accurate temperature prediction is essential for battery safety, performance, and longevity.

Dataset
The dataset includes:

Voltage_measured, Current_measured, Time, Capacity, Temperature_measured (target), and other operational metrics.
Project Steps
Data Preprocessing: Cleaned and prepared the dataset.
Exploratory Data Analysis (EDA): Visualized relationships between features and temperature.
Modeling: Built a linear regression model to predict battery temperature.
Evaluation: Assessed the model with MAE, MSE, RMSE, and R².
Results
The model helps in understanding factors influencing temperature, supporting proactive thermal management.

Usage
Clone the repository.
Open the Jupyter notebook for code and insights.
Dataset: https://github.com/fmardero/battery_aging
Requirements
Python, Jupyter, pandas, scikit-learn, matplotlib, seaborn
