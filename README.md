# Subscription Churn Prediction

This project applies machine learning models—Decision Trees and Random Forests—to predict customer churn in a subscription-based streaming service. The goal is to identify customers who are likely to cancel their subscriptions and provide business insights that can help improve customer retention.

## Project Structure

```
subscription-churn-prediction/
├── report.pdf                # Project report with analysis and results
├── customer_churn.csv        # Dataset containing customer information
└── prediction.ipynb          # Jupyter notebook with full implementation
```

## Overview

The project involves:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Building and evaluating Decision Tree and Random Forest models
- Analyzing model performance using metrics such as accuracy, precision, recall, and F1 score
- Visualizing decision trees and feature importances
- Providing business recommendations based on findings

## Dataset Features

The dataset includes:

- **Demographics**: Age, Subscription Length
- **Usage Behavior**: Watch Time, Number of Logins, Preferred Content Type
- **Subscription Details**: Membership Type, Payment Method, Payment Issues
- **Customer Support**: Number of Complaints, Resolution Time
- **Target Variable**: Churn (1 = customer churned, 0 = customer retained)

## Models Used

- **Decision Tree Classifier**: Built and tuned using scikit-learn's `GridSearchCV`.
- **Random Forest Classifier**: Used to improve accuracy and interpret feature importance.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Requirements

To run the notebook, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Project

1. Open `prediction.ipynb` in Jupyter Notebook or Google Colab.
2. Upload the dataset file `customer_churn.csv` when prompted.
3. Run the notebook cells sequentially to see data analysis, model training, and evaluation.
