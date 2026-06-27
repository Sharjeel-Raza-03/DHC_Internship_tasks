Heart Disease Prediction
Project Overview
This project predicts whether a person is at risk of heart disease using machine learning.

It uses the Heart Disease UCI dataset and trains classification models to predict heart disease based on health-related features.

Objective
Build a machine learning model to classify whether a patient has heart disease or not.

Dataset
Dataset used:

heart.csv
The dataset contains patient health information such as age, blood pressure, cholesterol, chest pain type, and heart rate.

Target Column
target
Target values:

0 = No heart disease
1 = Heart disease
Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
Models Used
Logistic Regression
Decision Tree Classifier
Project Steps
Loaded the dataset
Checked dataset shape and columns
Checked missing values
Removed duplicate rows
Performed exploratory data analysis
Visualized data using charts
Split data into training and testing sets
Applied feature scaling
Trained Logistic Regression model
Trained Decision Tree model
Evaluated models using accuracy, confusion matrix, classification report, and ROC curve
Checked feature importance
Evaluation Metrics
The models were evaluated using:

Accuracy
Confusion Matrix
Classification Report
ROC Curve
ROC-AUC Score
Visualizations
The notebook includes:

Target distribution plot
Age distribution plot
Gender vs heart disease plot
Chest pain type vs heart disease plot
Cholesterol box plot
Correlation heatmap
Confusion matrix
ROC curve
Feature importance plot
How to Run
Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn
Run the Jupyter Notebook:

jupyter notebook
Open and run:

Task_3_Heart_Disease_Prediction.ipynb
Results
Logistic Regression and Decision Tree models were trained and compared.

The models were able to predict heart disease risk using the given health features.

Feature importance helped identify which health factors had more impact on prediction.
