# Insurance Premium Prediction Competition

This repository contains the solution for the **Insurance Premium Prediction Competition**, where the goal was to predict the **Premium Amount** based on the provided dataset.

## Objective

Predict the **Premium Amount** for each row in the test dataset. Submissions are evaluated using the **Root Mean Squared Logarithmic Error (RMSLE)**.

---

## Dataset Overview

The dataset was generated using a deep learning model trained on the **Insurance Premium Prediction dataset**. Feature distributions are similar but not identical to the original dataset.

### Files

- **train.csv**: Training data with the target variable `Premium Amount`.  
- **test.csv**: Test data without the target variable.  
- **sample_submission.csv**: Submission format file.  

---

## Evaluation Metric

Submissions are evaluated using the **Root Mean Squared Logarithmic Error (RMSLE)**:

---

## Best Score

**Achieved RMSLE:** **1.06643**

---

## Solution Summary

- **EDA & Preprocessing**: Identified trends, handled missing data, and scaled features.  
- **Feature Engineering**: Created new features to enhance predictions.  
- **Model**: Used **LightGBM** for training, with hyperparameter tuning for optimal performance.  
- **Evaluation**: Applied cross-validation to ensure robustness.

---

## Submission

1. Generate predictions on `test.csv` using the trained LightGBM model.  
2. Format predictions as per `sample_submission.csv`.  
3. Submit the file.

---

## Acknowledgments

Thanks to the organizers for providing this dataset and the opportunity to refine predictive modeling skills.
