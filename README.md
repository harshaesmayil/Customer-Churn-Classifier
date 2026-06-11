# Customer Churn Prediction Classifier

## Project Overview

This project predicts whether a telecom customer is likely to churn using machine learning classification models.

The objective is to help businesses identify customers at risk and support customer retention strategies.

---

## Dataset

Dataset Used:

Telco Customer Churn Dataset

Dataset Source:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Place dataset inside:

data/raw/

Dataset File:

WA_Fn-UseC_-Telco-Customer-Churn.csv

---

## Folder Structure

project/

├── data/

│   ├── raw/

│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv.csv

│   ├── processed/

│   └── processed_churn.csv

│

├── models/

│   └── churn_classifier.pkl

│

├── notebooks/

│   └── 01_eda_customer_churn.ipynb

│

├── reports/

│   └── evaluation_report.md

│

├── src/

│   ├── preprocess.py

│   ├── train_model.py

│   ├── evaluate.py

│   └── predict.py

│

├── requirements.txt

├── .gitignore

└── README.md

---

## Features Implemented

* Exploratory Data Analysis (EDA)
* Missing value handling
* Data preprocessing
* Feature encoding
* Feature scaling
* Model training
* Model evaluation
* Customer churn prediction

---

## Models Tested

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier

---

## Best Model

Selected Model:

Logistic Regression

Reason:

Provided the strongest balance across Accuracy, Precision, Recall, F1-score and ROC-AUC.

---

## How To Run

Install dependencies:

pip install -r requirements.txt

Run preprocessing:

python src/preprocess.py

Run training:

python src/train_model.py

Run evaluation:

python src/evaluate.py

Run prediction:

python src/predict.py

---

## Author

Harsha Esmayil
