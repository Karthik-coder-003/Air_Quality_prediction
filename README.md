Air Quality Analysis and Prediction
This project focuses on the analysis and prediction of air quality in Tamil Nadu, India, using data from the Central Pollution Control Board (CPCB) for the year 2014. The analysis includes data cleaning, visualization, and regression modeling to understand pollutant levels and predict their values.

Contents:
Data Cleaning and Preparation: The data from the CPCB is cleaned, preprocessed, and prepared for analysis. Missing values are handled, data types are adjusted, and categorical variables are encoded for modeling.

Data Visualization: The cleaned data is visualized to gain insights into pollutant levels over time (by month) and their distribution. Visualizations include bar charts, pie charts, and line graphs for convenient interpretation.

Linear Regression Modeling: Linear regression models are implemented to predict pollutant levels (SO2, NO2, and RSPM/PM10). The accuracy of each model is evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R2).

Random Forest Regression Modeling: Random Forest regression models are applied for predicting pollutant levels. The performance of these models is assessed using Root Mean Squared Error (RMSE) and R-squared (R2).

Usage:
Data Cleaning and Preparation: The provided Python script demonstrates the steps to clean and preprocess the data, making it suitable for analysis.

Data Visualization: Visualizations are generated using libraries like Matplotlib and Seaborn, providing insights into pollutant levels and their distribution.

Regression Modeling: Linear regression and Random Forest regression models are implemented using scikit-learn. The provided scripts show how to train these models, make predictions, and evaluate their performance.

Requirements:
Python 3.x
Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn
Dataset:
The dataset used in this project contains daily air quality measurements for various pollutants in Tamil Nadu, India, sourced from the Central Pollution Control Board (CPCB) for the year 2014.
