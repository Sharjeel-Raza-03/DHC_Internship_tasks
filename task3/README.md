# Heart Disease Prediction

## Project Overview

This project predicts whether a person is at risk of heart disease using machine learning.

It uses the Heart Disease UCI dataset and trains classification models to predict heart disease based on health-related features.

## Objective

Build a machine learning model to classify whether a patient has heart disease or not.

## Dataset

Dataset used:

```text
heart.csv
````

The dataset contains patient health information such as age, blood pressure, cholesterol, chest pain type, and heart rate.

## Target Column

```text
target
```

Target values:

```text
0 = No heart disease
1 = Heart disease
```

## Libraries Used

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## Models Used

```text
Logistic Regression
Decision Tree Classifier
```

## Project Steps

1. Loaded the dataset
2. Checked dataset shape and columns
3. Checked missing values
4. Removed duplicate rows
5. Performed exploratory data analysis
6. Visualized data using charts
7. Split data into training and testing sets
8. Applied feature scaling
9. Trained Logistic Regression model
10. Trained Decision Tree model
11. Evaluated models using accuracy, confusion matrix, classification report, and ROC curve
12. Checked feature importance

## Evaluation Metrics

The models were evaluated using:

```text
Accuracy
Confusion Matrix
Classification Report
ROC Curve
ROC-AUC Score
```

## Visualizations

The notebook includes:

```text
Target distribution plot
Age distribution plot
Gender vs heart disease plot
Chest pain type vs heart disease plot
Cholesterol box plot
Correlation heatmap
Confusion matrix
ROC curve
Feature importance plot
```

## How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open and run:

```text
Task_3_Heart_Disease_Prediction.ipynb
```

## Results

Logistic Regression and Decision Tree models were trained and compared.

The models were able to predict heart disease risk using the given health features.

Feature importance helped identify which health factors had more impact on prediction.

```
```
