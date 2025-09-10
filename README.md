House Price Prediction Project 🏠💻

This project demonstrates a machine learning approach to predicting house prices using multiple features such as area, bedrooms, bathrooms, stories, and more. The goal is to estimate the price of a house based on its characteristics.

Features Used

Numeric features: area, bedrooms, bathrooms, stories, parking

Categorical features: mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

Engineered features:

price_per_area

area_per_bedroom

area_per_bathroom

stories_area

Interaction features such as area * bedrooms

Model

Algorithm: Linear Regression

Library used: scikit-learn

Performance Metrics

Mean Absolute Error (MAE): 570,464

Root Mean Squared Error (RMSE): 756,657

R² Score: 0.868

The model explains ~87% of the variation in house prices, showing strong predictive power given the dataset size of 546 houses.

Tools & Technologies

Python 🐍

pandas & NumPy for data processing

scikit-learn for modeling
