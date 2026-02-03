# Task 9 – Credit Card Fraud Detection

## Objective
The objective of this task is to detect fraudulent credit card transactions using machine learning techniques while handling highly imbalanced data.

## Dataset
Due to dataset accessibility constraints, a synthetic dataset was generated using `make_classification()` from scikit-learn to simulate real-world credit card fraud scenarios with severe class imbalance.

- Class 0: Normal Transactions  
- Class 1: Fraudulent Transactions  

## Approach
- Generated an imbalanced dataset to simulate fraud detection
- Performed exploratory data analysis and class distribution visualization
- Split data into training and testing sets using stratified sampling
- Trained a classification model
- Evaluated model performance using Precision, Recall, F1-score, and Confusion Matrix

## Evaluation Metrics
Since fraud detection is a highly imbalanced problem, accuracy alone is not reliable. Therefore, the following metrics were used:
- Precision
- Recall
- F1-score
- Confusion Matrix

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

## Conclusion
This task demonstrates the importance of handling class imbalance and selecting appropriate evaluation metrics when building machine learning models for fraud detection in real-world financial applications.

## File
- `Task9_Credit_Card_Fraud_Detection.ipynb`
