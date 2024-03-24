# Waze User Churn Prediction Project

## Overview

Waze's free navigation app has a thriving community of users and contributors. To ensure the continued growth and satisfaction of its user base, this project focuses on predicting and preventing user churn. Churn refers to the number of users who stop using the app or uninstall it. By analyzing user behavior and developing a churn prediction model, we aim to answer key questions:

- Who are the users most likely to churn?
- Why do users churn?
- When do users churn?

## Ethical Considerations

Predictive modeling, especially in the context of user churn, raises ethical questions. Here are some considerations:

- **Model Consequences**:
    - **False Negatives**: If our model predicts a user won't churn when they actually will, Waze might miss the opportunity to retain them.
    - **False Positives**: If our model predicts a user will churn when they won't, Waze may take unnecessary actions, potentially leading to an annoying experience for loyal users.

- **Weighing Benefits and Problems**: The proactive measures Waze takes based on our model's predictions may have unintended effects. Follow-up analysis to evaluate these measures is essential. If the measures are reasonable and effective, the benefits will likely outweigh the problems.

- **Proceeding with the Model**: Given the lack of significant risks, it's advisable to proceed with building the churn prediction model.

## Project Steps

Follow these steps to understand and reproduce the project:

1. Import Libraries: Import necessary.
2. Load and Explore Data: Load dataset and perform exploratory data analysis (EDA).
3. Preprocessing: Preprocess data by encoding and scaling features.
4. Model Training: Train multiple machine learning models, Random Forest, snd XGBoost.
5. Hyperparameter Tuning: Optimize hyperparameters for the models.
6. Optimization Results: Display the best hyperparameters and accuracy.
7. End Experiment: Conclude the customer churn ML experiment.

## Dependencies

The following Python libraries and dependencies are required for this project:

- NumPy
- Pandas
- Scikit-learn
- Random Forest
- XGBoost
- Matplotlib
- Seaborn



