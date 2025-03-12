# disease_prediction_hkd
This system is a multi-disease prediction web application built using Streamlit and Machine Learning models. It allows users to input health-related parameters and predicts whether a person is likely to have Diabetes, Heart Disease, or Kidney Disease. The system is structured into three main sections, each dedicated to a specific disease prediction:

1. Functional Overview

 Diabetes Prediction:
Takes user inputs such as glucose level, BMI, insulin, blood pressure, and other parameters.
Uses a pre-trained machine learning model (diabetes.pkl) to predict if the person has diabetes.
Classifies BMI and glucose levels into specific ranges for better prediction accuracy.

Heart Disease Prediction:
Collects details like age, chest pain type, cholesterol, blood pressure, and more.
Uses a pre-trained model (heart.pkl) to classify if the person has heart disease.

Kidney Disease Prediction:
Accepts detailed inputs like blood pressure, glucose levels, red blood cell count, and creatinine levels.
Uses a pre-trained model (kidney.pkl) to determine the likelihood of kidney disease.

Result Display:
After processing the user input, the system displays the result as a success message indicating whether the person has the disease or not.


2. Tools and Technologies Used
Tool/Technology	Purpose
Python-Programming language used to build the application.
Streamlit-Framework for creating interactive web applications.
scikit-learn-For training and loading machine learning models.
pickle-To save and load pre-trained models.
Pandas-For data manipulation and preprocessing.
NumPy-For numerical computations.
Streamlit Option Menu	For creating a sidebar with a selection menu.
