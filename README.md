# Insurance Premium Prediction Competition

This repository contains the solution for the **Insurance Premium Prediction Competition**, where the goal was to predict the **Premium Amount** based on the provided dataset.

## Objective

The competition's objective is to predict the **Premium Amount** for each row in the test dataset. Submissions are evaluated using the **Root Mean Squared Logarithmic Error (RMSLE)**.

## Dataset Overview

The dataset for this competition was generated using a deep learning model trained on the **Insurance Premium Prediction dataset**. The feature distributions are similar but not identical to the original dataset. Participants were encouraged to explore the differences and leverage the original dataset for potential performance improvements.

### Files

1. **train.csv**
   - Contains the training data with the target variable: `Premium Amount`.

2. **test.csv**
   - Contains the test data without the target variable.

3. **sample_submission.csv**
   - Provides the submission format. Participants are required to predict the `Premium Amount` for each row in the test set.

---

## Evaluation Metric

Submissions are evaluated using the **Root Mean Squared Logarithmic Error (RMSLE)**:

## Best Score

**Achieved RMSLE:** **1.06643**

---

## Solution Approach

### 1. Data Exploration & Preprocessing
- Performed EDA to identify trends, outliers, and missing values.
- Handled missing data and scaled features appropriately.

### 2. Feature Engineering
- Created new features and transformed existing ones to enhance predictive power.
- Explored the use of original Insurance Premium Prediction dataset for additional insights.

### 3. Model Selection & Training
- Experimented with various machine learning models, including:
  - Gradient Boosting (XGBoost, LightGBM)
  - Ensemble models
- Tuned hyperparameters using techniques like grid search and Bayesian optimization.

### 4. Evaluation
- Used cross-validation to assess model performance and prevent overfitting.
- Selected the best-performing model based on RMSLE on the validation set.

---

## Submission

To make a submission:
1. Generate predictions on the test set using the trained model.
2. Format the predictions according to `sample_submission.csv`.
3. Submit the file.

---

## Acknowledgments

Special thanks to the organizers for providing a challenging dataset and an opportunity to improve skills in predictive modeling.

---
