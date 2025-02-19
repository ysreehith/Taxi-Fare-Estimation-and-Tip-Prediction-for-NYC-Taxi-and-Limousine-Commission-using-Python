# Taxi-Fare-Estimation-and-Tip-Prediction-for-NYC-Taxi-and-Limousine-Commission-using-Python

## Project Overview
This project analyzes NYC taxi trip data to estimate fare amounts before a ride and predict whether a customer will leave a tip. The analysis is conducted for the New York City Taxi and Limousine Commission (TLC) using machine learning techniques.

## Data Source
The dataset used in this project comes from NYC TLC, containing taxi trip records with details such as trip duration, distance, payment type, and total fare.

## Project Objectives
- Perform exploratory data analysis (EDA) and clean the dataset.
- Conduct hypothesis testing on the relationship between payment type and fare amount.
- Build a regression model to estimate taxi fares before the ride.
- Develop a classification model to predict if a customer will leave a tip.

## Methodology
### Data Preprocessing:
- Handled missing values and inconsistencies.
- Identified and corrected anomalies in trip distance, passenger count, and fare amounts.

### Exploratory Data Analysis:
- Analyzed fare distribution, payment trends, and trip patterns.

### Machine Learning Models:
- **Regression Model:** Used Linear Regression to estimate fare amounts.
- **Classification Model:** Employed Random Forest and XGBoost to predict tip likelihood.

## Key Findings
- Higher trip distances and certain pickup locations correlated with higher fares.
- Credit card payments had a higher probability of including tips compared to cash payments.
- The best-performing classification model achieved high accuracy in predicting tip behavior.

## Tools & Libraries
- **Python:** Pandas, NumPy, Seaborn, Matplotlib
- **Machine Learning:** Scikit-learn, XGBoost
- **Statistical Analysis:** Scipy (Hypothesis Testing)
