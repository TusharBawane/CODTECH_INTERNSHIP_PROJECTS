# Customer Churn Analysis & Prediction

## Problem Statement
Customer churn is a major challenge for businesses, especially in the telecom industry.  
This project aims to predict whether a customer is likely to churn based on their historical and behavioral data, helping businesses take early retention actions.

---

## Dataset
- Telco Customer Churn Dataset
- Format: CSV
- Contains customer demographics, service usage, billing details, and churn status

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

---

## Approach
1. Loaded and explored the dataset to understand structure and features
2. Performed data cleaning and handled missing values
3. Encoded categorical variables for machine learning
4. Split the data into training and testing sets
5. Built a Logistic Regression model
6. Evaluated the model using accuracy, confusion matrix, and classification report

---

## Model Results
- Accuracy: ~78.5%
- The model performs well in identifying non-churn customers
- Churn detection recall is moderate and can be improved

---

## Business Insights
1. The model achieved around 78.5% accuracy, indicating reasonable overall performance in predicting customer churn.
2. The model performs better in identifying non-churn (loyal) customers, as shown by higher precision and recall for non-churn cases.
3. Recall for churn customers is moderate, meaning some customers who actually churned were not identified by the model.
4. Features such as tenure and monthly charges play an important role in churn prediction, as they reflect customer loyalty and pricing impact.
5. The model can be used to identify high-risk customers early and support retention strategies such as targeted offers and improved customer support.

---

## Conclusion
This project demonstrates how machine learning can be applied to analyze customer behavior and predict churn.  
While the model provides useful insights, further improvements such as feature scaling, class balancing, or advanced models can enhance churn prediction performance.
