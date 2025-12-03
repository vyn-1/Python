✈️ Aircraft Cost Prediction — Python Project
📌 Overview

This project builds a predictive machine learning model to estimate aircraft manufacturing cost using linear regression techniques. Using a dataset containing four key engineering and performance variables (X1–X4), the project demonstrates the complete workflow of preparing data, splitting it into training and testing sets, fitting a model, evaluating performance, and generating insights.

The work follows instructional steps from the University of West Florida's Tools for Data Science materials and uses Python’s scientific computing stack for reproducibility and clarity.

📂 Project Features
✔ Data Preparation

Loads aircraft dataset into a pandas DataFrame.

Constructs feature matrix X using variables X1, X2, X3, X4.

Defines target variable Y representing aircraft cost.

Splits data into training (80%) and testing (20%) sets using train_test_split.

Example output shown:

Training set: (18, 4)

Test set: (5, 4) 

Python project code

✔ Machine Learning Model

Implements a Linear Regression model using scikit-learn.

Fits the model on the training data.

Generates predictions on the test set.

Evaluates model accuracy and interprets numerical outputs.

✔ Tools & Libraries Used

pandas for data management

numpy for numerical computation

scikit-learn for modeling (LinearRegression, train_test_split)

Jupyter Notebook / Quarto environment for interactive development (as shown in outputs)

🎯 Purpose

This project is designed to:

Practice foundational supervised machine learning concepts

Apply linear modeling to real-world engineering data

Explore relationships between aircraft specifications and manufacturing cost

Build interpretable models useful for predictive analytics and decision making

📘 How to Run

Install required packages:

pip install pandas numpy scikit-learn


Open the notebook or Python script.

Run each cell or section in order.

Review model output, coefficients, error metrics, and predictions.
