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

## Project Screenshots

### Repository Structure

![Repo]<img width="464" height="645" alt="image" src="https://github.com/user-attachments/assets/9b951854-f09b-4196-a968-16d3d4e3fa86" />


### EDA

<img width="719" height="483" alt="Screenshot 2026-06-12 000404" src="https://github.com/user-attachments/assets/e6fa715e-348c-4c53-b0af-0013205f3901" />
<img width="708" height="463" alt="Screenshot 2026-06-12 000344" src="https://github.com/user-attachments/assets/2ba751b7-8443-4f85-b26b-487d3eba99c3" />
<img width="706" height="461" alt="Screenshot 2026-06-12 000325" src="https://github.com/user-attachments/assets/c117a3d2-b969-4fda-a975-e372fe67515d" />
<img width="797" height="698" alt="Screenshot 2026-06-12 000310" src="https://github.com/user-attachments/assets/84d09a3d-f0c4-487a-a755-c40636d68ae0" />



### Training

<img width="694" height="210" alt="Screenshot 2026-06-12 000158" src="https://github.com/user-attachments/assets/422e4a7a-f254-4327-ad59-0d8fe69fb114" />


### Evaluation

<img width="197" height="117" alt="Screenshot 2026-06-12 000012" src="https://github.com/user-attachments/assets/1878547d-d0f4-4431-99c2-329338657965" />
<img width="201" height="98" alt="Screenshot 2026-06-12 000005" src="https://github.com/user-attachments/assets/e8af9786-6e70-46ec-b02d-5d4c54e747b3" />
<img width="593" height="192" alt="Screenshot 2026-06-11 235954" src="https://github.com/user-attachments/assets/16f9ab3a-36e4-4d58-9989-d21292f8ca28" />


### Prediction

<img width="521" height="452" alt="Screenshot 2026-06-11 235832" src="https://github.com/user-attachments/assets/1e8a8683-af43-4317-abac-976b795ede32" />


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
