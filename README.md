# 🏃🔥 Calories Burnt Prediction using Machine Learning

## Project Overview

This project aims to predict the number of calories burned during exercise using Machine Learning techniques.
By analyzing parameters such as age, gender, height, weight, heart rate, body temperature, and exercise duration, the model estimates calories burned with high accuracy.

This project is part of my 50 Days – 50 Projects Challenge to strengthen my Data Science and Machine Learning skills.

## Dataset Information

The project uses two datasets:

exercise.csv – Contains user exercise-related details

calories.csv – Contains calories burned information

### After merging both datasets, the final dataset includes:

User_ID

Gender

Age

Height

Weight

Duration

Heart_Rate

Body_Temp

Calories

## Technologies Used

Python 🐍

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

## Project Workflow

Data Collection

Data Preprocessing

Handling missing values

Encoding categorical variables

Exploratory Data Analysis (EDA)

Feature Selection

Model Building

Model Evaluation

## Machine Learning Model

Model Used: XGBoost Regressor / Random Forest Regressor

Evaluation Metrics:

Mean Absolute Error (MAE)

R² Score

The model achieves strong predictive performance in estimating calories burned.

## Results

The trained model successfully predicts calories burned based on physical and exercise parameters.
Feature importance analysis shows that Duration and Heart Rate significantly impact calorie burn prediction.

## Future Improvements

Hyperparameter tuning

Deploying using Streamlit

Adding real-time user input form

Model optimization
