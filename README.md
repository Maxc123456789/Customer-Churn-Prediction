Customer Churn Prediction

Project Overview

Customer churn prediction is an important task for businesses to retain customers. This project analyzes customer data from a telecom company and builds a machine learning model to predict customer churn.

Dataset

Name: Telco Customer Churn Dataset

Source: Kaggle

Description: The dataset contains customer demographic information, account details, service usage, and churn status.

File: WA_Fn-UseC_-Telco-Customer-Churn.csv

Dependencies

Install the required Python libraries using:

pip install pandas numpy matplotlib seaborn scikit-learn

Project Workflow

Data Preprocessing:

Handle missing values

Convert categorical variables to numerical format

Scale numerical features

Split dataset into training and testing sets

Exploratory Data Analysis (EDA):

Visualizing churn distribution

Analyzing correlations between features

Identifying important predictors

Model Training:

Using a Random Forest Classifier to predict churn

Training on 80% of the data, testing on 20%

Model Evaluation:

Accuracy score

Classification report (precision, recall, F1-score)

Confusion matrix visualization

Running the Project

Download the dataset and place it in the data/ folder.

Run the Python script:

python customer_churn.py

View the accuracy and classification report in the console.

The confusion matrix will be displayed as a heatmap.

Results

The model achieves an accuracy of approximately 80% (varies based on dataset split).

Important predictors of churn include contract type, tenure, and monthly charges.