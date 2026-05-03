# Predicting-Urban-Benzene-Concentration-Using-IoT-Gas-Sensor-Arrays
Predicting Urban Benzene Concentration Using IoT Gas Sensor Arrays
A machine learning project that predicts benzene concentration in urban air using low-cost metal oxide gas sensors, demonstrating that intelligent sensor arrays can serve as viable alternatives to expensive laboratory-grade reference analyzers.

Objectives

Predict benzene (C6H6) concentration in microg/m3 using only metal oxide sensor readings and environmental variables
Compare linear and ensemble machine learning approaches on real-world IoT sensor data
Identify which sensors contribute most to prediction accuracy
Demonstrate a realistic IoT deployment scenario by excluding reference analyzer data from model inputs

Dataset

Name: UCI Air Quality Dataset
Source: UCI Machine Learning Repository
Link: https://archive.ics.uci.edu/dataset/360/air+quality
Citation: De Vito, S. et al. (2008). On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario. Sensors and Actuators B: Chemical, 129(2), 750-757.

9,358 hourly observations
5 metal oxide chemical sensors (PT08.S1 through PT08.S5)
Environmental variables: temperature, relative humidity, absolute humidity
Collected at road level in an Italian city, March 2004 – February 2005
Target variable: C6H6(GT) — benzene concentration in microg/m3

Tools and Libraries

Language: Python 3
Environment: Google Colab
Data: numpy, pandas, ucimlrepo
Visualization: matplotlib, seaborn
Modeling: scikit-learn (LinearRegression, RandomForestRegressor, GradientBoostingRegressor, GridSearchCV, KNNImputer, StandardScaler)

Colab Notebook
NotebookDescriptionair_quality_project.ipynbFull analysis: EDA, preprocessing, modeling, evaluation

How to Run

Go to Runtime → Run all 
The notebook will automatically install ucimlrepo and download the dataset — no manual downloads required
All outputs, plots, and model results will generate in order


Author:
Cem Cereb

ISOM 835 — Predictive Analytics and Machine Learning
