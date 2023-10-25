# "Credit Card Fraud Detection and Prevention"

## Summary

In this project, I tackled the challenge of credit card fraud detection using machine learning techniques. With a dataset containing anonymized credit card transactions, I aimed to identify fraudulent transactions amidst a majority of non-fraudulent ones. Through extensive analysis and model evaluation, I employed advanced algorithms to achieve high accuracy and fraud detection capabilities. The goal was to develop robust models that could accurately identify fraudulent activities while minimizing false positives.

## Approach

I started by exploring the dataset and addressing its class imbalance using the SMOTE technique, ensuring a balanced representation of both fraud and non-fraud cases. Four models—Logistic Regression, XGBoost, Decision Tree, and Random Forest—were trained, tuned, and evaluated for their performance metrics, focusing on accuracy, F1-score, and ROC AUC score. Rigorous evaluation and hyperparameter tuning led to the selection of the most effective model.

## Solution

The XGBoost model emerged as the most powerful tool, delivering exceptional results with a 99.95% accuracy, 81.14% F1-score, and a remarkable ROC AUC score of 97.24%. To handle class imbalance, I utilized the SMOTE technique, enhancing the model's sensitivity to detect fraudulent transactions. To enhance the solution further, I utilized ensemble methods, combining the strengths of XGBoost and Random Forest. The resulting ensemble model demonstrated significant improvements, especially in identifying fraudulent transactions. Additionally, I have shared insights into the challenges faced and proposed preventive measures for future fraud instances, making it a comprehensive resource for understanding the intricacies of Credit Card Fraud Detection.
<b> Link to Notebook: [Fraud Detection](https://github.com/Safrin03/Sentiment-Analysis-Amazon-Alexa-Reviews/blob/main/Amazon-Alexa-Reviews-Sentiment-Analysis.ipynb) </b>

## Data Source

<b>Check out this [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) to find the datasets of this project.</b>
