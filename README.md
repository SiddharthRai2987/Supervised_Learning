## Supervised Learning Projects

# Overview
This repository contains machine learning projects focused on prediction tasks using supervised learning techniques. It consists of two main parts:

# Part A: Predicting the price of pre-owned cars in India

# Part B: Predicting employee attrition for HR analytics

## Part A: Used Car Price Prediction
# Context
The Indian market for pre-owned cars is growing rapidly. As a senior data scientist at Cars4U, the task is to build a pricing model to predict the value of used cars, assisting the business in profitable pricing strategies.

# Objective
Build a linear regression model to predict used car prices.

Explore and visualize the dataset for actionable insights and recommendations.

# Data Description
The dataset contains attributes for cars sold in various locations, including:

Name, Location, Year, Kilometers_Driven

Fuel_Type, Transmission, Owner_Type, Mileage

Engine, Power, Seats, New_Price, Price

See notebook for the full data dictionary.

# How to Run
Open Supervised_Learning_Project_Part_A.ipynb in Jupyter/Colab.

Ensure the dataset is available as specified (used_cars_data.csv).

Run each cell sequentially for data preparation, modeling, and evaluation.

# Key Libraries Used
pandas, numpy, matplotlib, seaborn

sklearn (preprocessing, model selection, evaluation)

# Part B: Employee Attrition Prediction
Context
McCurr Healthcare Consultancy spends substantially on employee retention. The goal is to lower costs by identifying employees most at risk of leaving and target incentives accordingly.

# Objective
Analyze employee data to find patterns in attrition.

Build predictive models for attrition risk using classification techniques.

# Data Description
The dataset contains demographic and job-related information such as:

EmployeeNumber, Attrition, Age, BusinessTravel, Department, Education

JobSatisfaction, MonthlyIncome, Overtime, YearsAtCompany, and more.

See notebook for the complete feature list and descriptions.

# How to Run
Open Supervised_Learning_Project_Part_B.ipynb in Jupyter/Colab.

Use the HR dataset (HR_Employee_Attrition_Dataset.xlsx).

Execute all notebook cells to preprocess, visualize, and build classification models.

Key Libraries Used
pandas, numpy, matplotlib, seaborn

sklearn (preprocessing, model selection, metrics, classifiers)

Setup Instructions
Install required Python libraries via:

text
pip install pandas numpy matplotlib seaborn scikit-learn
Download datasets and place in the appropriate directory.

# Results & Insights
Used Car Price Prediction: Key factors influencing price and model accuracy, plus recommendations for pricing strategies.

Employee Attrition Prediction: Important attrition predictors and potential policies for improved retention.

# Contributing
Pull requests for improvements are welcome. For major changes, please open an issue first to discuss what you would like to change.

License
Distributed under the MIT License. See LICENSE file for details.

