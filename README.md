# Credit Card Approval Prediction

A supervised machine learning project that predicts whether a credit card application will be approved or rejected.

## Project Overview

Banks receive large numbers of credit card applications, making manual review time-consuming and prone to inconsistency. This project demonstrates how a machine learning classification model can help automate the approval process.

The project uses Python and scikit-learn to preprocess application data, train a logistic regression classifier, tune model hyperparameters, and evaluate performance on unseen data.

## Machine Learning Workflow

The project includes:

- Handling missing values
- Imputing categorical and numerical data
- One-hot encoding categorical features
- Separating features and target variables
- Train/test splitting
- Feature scaling with `StandardScaler`
- Logistic Regression classification
- Model evaluation using a confusion matrix
- Hyperparameter tuning with `GridSearchCV`
- Evaluation of the optimized model on unseen test data

## Model Performance

The final optimized model achieved approximately:

**79.4% test accuracy**

The grid search cross-validation score was approximately:

**81.8%**

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- Jupyter Notebook

## Key Skills Demonstrated

- Data preprocessing
- Feature engineering
- Supervised machine learning
- Binary classification
- Model evaluation
- Cross-validation
- Hyperparameter tuning
- Avoiding data leakage

## Repository Contents

`credit_card_approval.ipynb` — Complete machine learning analysis and modeling workflow.

## Future Improvements

Potential improvements include comparing Logistic Regression with additional classification algorithms such as Random Forest, Gradient Boosting, and Support Vector Machines, as well as evaluating models using precision, recall, F1-score, and ROC-AUC.

## Author

Michael Boyce
