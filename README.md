🏡 House Rent Prediction – Machine Learning Project

This project focuses on predicting house rent prices using Machine Learning techniques.
The model is trained on a real dataset containing property features such as location, size, number of rooms, furnishing status, and more.

📌 Project Overview

The goal is to build a regression model that can accurately estimate the rent price of a house based on multiple features.
The project includes EDA, data preprocessing, model training, evaluation, and results visualization.

📂 Project Structure
├── House_Rent.ipynb        # Full analysis, EDA, preprocessing, and model building
├── House_Rent_Dataset.csv  # Dataset used for training the model
└── README.md               # Project documentation

🎯 Objectives

Understand key factors that influence rent prices

Clean and preprocess the dataset

Visualize relationships between features

Train multiple regression models

Compare models and select the best one

Evaluate model performance using standard metrics

🛠️ Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔍 Workflow Summary

Data Loading & Cleaning

Remove duplicates

Handle missing values

Encode categorical features

Exploratory Data Analysis (EDA)

Distribution plots

Correlation heatmap

Feature relationships

Model Building

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Model Evaluation

MAE

MSE

RMSE

R² Score

📈 Results

The notebook includes:

Model performance comparison

Feature importance visualization

Best-performing model selection

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/Sobhy2005Adel/-House-Rent-Prediction-Machine-Learning-Project


Install dependencies:

pip install -r requirements.txt


Open the Notebook:

jupyter notebook House_Rent.ipynb

📥 Dataset Description

The dataset contains:

BHK (number of bedrooms)

Size (sqft)

Bathroom count

Location

Furnishing status

Floor details

Rent amount (target)

🔮 Future Improvements

Deploy the model using Streamlit

Add more advanced models

Hyperparameter tuning

Add external features (schools, transport, safety index)
