# Titanic Survival Prediction with XGBoost

This repository contains a machine learning model to predict the survival of passengers on the Titanic. The model is built using XGBoost and deployed via a Streamlit web application.

Features
1. Data Preprocessing: Handles missing values, encodes categorical variables, and scales numerical features using Pandas and Numpy.
2. Model Training: Utilizes XGBoost for training on the Titanic dataset.
3. Streamlit App: An interactive web application to input passenger details and get survival predictions.

Streamlit App Features
- Passenger Details Input: Allows users to input various passenger details such as class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and port of embarkation.
- Prediction: Provides the survival prediction and the probability based on the input details.
- Data Overview: Option to view basic statistics and visualizations of the Titanic dataset.
- Feature Importance: Displays the importance of different features used in the model.
