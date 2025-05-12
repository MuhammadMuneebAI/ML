🫀 Ten-Year Coronary Heart Disease (CHD) Risk Predictor

This Streamlit application predicts an individual's 10-year risk of developing Coronary Heart Disease (CHD) using key health and lifestyle features. Built using a machine learning model trained on real-world cardiovascular health data, the app allows users to input various parameters such as age, gender, smoking habits, and education level to estimate their CHD risk.

💡 Features

Interactive UI built with Streamlit

Input controls for user-friendly risk prediction

Real-time CHD risk score output

Uses RandomForestRegressor for accurate predictions

Easy deployment via Streamlit Cloud


📊 Input Parameters

male: Gender (1 = Male, 0 = Female)

age: Age in years

education: Level of education (categorical)

currentSmoker: Smoking status (1 = Smoker, 0 = Non-smoker)

cigsPerDay: Average cigarettes per day (if smoker)


📦 Requirements

Python 3.7+

pandas, scikit-learn, streamlit, numpy
