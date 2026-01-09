# Amazon Reviews Sentiment Analysis

## Problem Statement
Understanding customer sentiment is important for businesses to improve products and services.  
This project aims to classify Amazon customer reviews as positive or negative using Natural Language Processing (NLP) and Machine Learning techniques.

---

## Dataset
- Amazon Reviews Dataset
- Format: Text
- Contains customer reviews with sentiment labels embedded in the text
- __label__1 represents negative sentiment
- __label__2 represents positive sentiment

---

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- Jupyter Notebook / VS Code

---

## Approach
1. Loaded and explored the raw text dataset
2. Extracted sentiment labels from review text
3. Performed basic text preprocessing (lowercasing and punctuation removal)
4. Converted text into numerical features using TF-IDF Vectorization
5. Split the dataset into training and testing sets
6. Built a Logistic Regression model
7. Evaluated the model using accuracy, confusion matrix, and classification report

---

## Model Results
- Accuracy: ~89%
- The model shows balanced performance for both positive and negative reviews
- Classification metrics indicate consistent predictions across both classes

---

## Business Insights
1. The model performs well on both positive and negative sentiment classification.
2. Customer feedback is almost evenly distributed between positive and negative reviews.
3. The model predicts positive reviews slightly better than negative reviews.
4. Negative reviews highlight areas where product or service improvements are required.
5. Sentiment analysis can help businesses monitor customer satisfaction and take data-driven decisions.

---

## Conclusion
This project demonstrates how NLP and Machine Learning techniques can be used to analyze large volumes of customer reviews.  
The sentiment analysis model provides reliable results and can support businesses in understanding customer opinions and improving overall customer experience.
