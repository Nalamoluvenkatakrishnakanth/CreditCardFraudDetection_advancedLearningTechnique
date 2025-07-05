# Fraud Detection Using XGBoost Machine Learning Algorithm

## Project Overview
This project focuses on detecting fraudulent transactions using a supervised machine learning approach. Fraudulent activity poses significant challenges to financial systems, and early detection helps prevent massive financial losses. Using Python and machine learning libraries, this project builds a logistic regression model to classify transactions as legitimate or fraudulent based on key features extracted from a given dataset.

## Usage
1.Launch Jupyter Notebook

2.Open FraudDetection.ipynb

3.Run each cell sequentially to:

    Load and preprocess data

    Train the logistic regression model

    Evaluate model performance

    Visualize results
## Methodology
1.Data Preprocessing:

    -Handled class imbalance using SMOTE Technique


2.Model Training:

        Used XGBclassifer from xgboost

        Trained on features selected from the dataset

        Split data into training and testing sets

        Used RFE for selecting best features

3.Performance Evaluation:

    -Accuracy

    -Precision

    -Recall

    -F1-score


## Result

| Metric    | Score           |
| --------- | --------------- |
| Accuracy  | 0.99            |
| Precision | 0.1             |
| Recall    | 0.1             |
| F1-Score  | 0.1             |


## Conclusion

This project demonstrates the use of xgboost for fraud detection, a critical task in financial sectors. The model performed well with high accuracy and balanced precision-recall, making it reliable for detecting fraudulent activities. While xgboost is interpretable and efficient, further enhancements could be made using more complex models such as Random Forests or neural networks, especially in cases of severe class imbalance or nonlinear relationships.

