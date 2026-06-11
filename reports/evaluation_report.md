# Model Evaluation Report

## Dataset Summary

Dataset: Telco Customer Churn Dataset

Target Column: Churn

Total Records: 7043

Original Input Features: 19

Features After Encoding: 30

Missing Values After Preprocessing: 0

---

## Problem Statement

The objective of this project is to predict whether a customer is likely to churn using customer information and service usage data.

Customer churn prediction helps businesses identify customers at risk of leaving and enables proactive retention strategies.

---

## Models Tested

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier

---

## Model Comparison

| Model               | Accuracy | Precision |   Recall | F1-score |  ROC-AUC |
| :------------------ | -------: | --------: | -------: | -------: | -------: |
| Logistic Regression | **0.82** |  **0.69** | **0.60** | **0.64** | **0.86** |
| Decision Tree       |     0.72 |      0.48 |     0.47 |     0.47 |     0.64 |
| Random Forest       |     0.79 |      0.65 |     0.47 |     0.55 |     0.84 |
| Gradient Boosting   |     0.81 |      0.67 |     0.54 |     0.60 | **0.86** |

---

## Best Model Selected

**Logistic Regression**

### Reason

* Highest overall Accuracy (**82%**)
* Highest Precision (**69%**)
* Highest Recall (**60%**)
* Highest F1-score (**0.64**)
* ROC-AUC (**0.86**) was among the strongest results

Logistic Regression produced the most balanced performance across customer churn prediction metrics and was selected as the final model.

---

## Confusion Matrix Interpretation

The evaluation results showed that the selected model performed well in identifying customers who are unlikely to churn.

From the classification report:

* Non-churn customers achieved a **Precision of 0.86**, indicating that most customers predicted to stay actually remained.
* Non-churn customers achieved a **Recall of 0.90**, meaning the model successfully identified most stable customers.

For churn prediction:

* Churn customers achieved a **Precision of 0.69**, meaning that approximately 69% of customers predicted to churn actually left.
* Churn customers achieved a **Recall of 0.60**, indicating that the model identified 60% of actual churn cases.

Although the model successfully detected many churn customers, some churn cases were still missed.

Improving recall would further strengthen churn detection performance and improve business usefulness.

---

## Business Interpretation

This model can help customer retention teams identify customers who are more likely to leave before churn occurs.

Potential business actions include:

* Targeted retention offers
* Loyalty programs
* Personalized customer communication
* Improved customer support
* Early intervention campaigns
* Customer satisfaction follow-ups

Using predictive analytics can reduce customer loss and improve long-term revenue retention.

---

## Limitations

* The dataset contains class imbalance between churn and non-churn customers.
* Customer behavior and market conditions may change over time.
* Model performance depends on historical customer information.
* Additional behavioral and engagement features may improve prediction quality.
* Some churn cases were not detected, as shown by the recall score.

---

## Future Improvements

Possible future enhancements include:

* Hyperparameter tuning for better optimization
* Cross-validation for more reliable evaluation
* Feature engineering to create stronger predictors
* Handling class imbalance techniques
* Ensemble model improvements
* Deployment as a prediction API or web application
* Continuous retraining using updated customer data

---

## Conclusion

The customer churn classification model achieved good predictive performance with an overall accuracy of approximately **82%**.

The selected Logistic Regression model demonstrated the strongest balance across Accuracy, Precision, Recall, F1-score, and ROC-AUC.

The model can support business decision-making by identifying customers with a higher probability of churn and enabling proactive retention strategies.
