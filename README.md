# Titanic Survival Prediction Using Random Forest

## Project Overview

This project develops a machine learning classification model to predict passenger survival on the Titanic using the Random Forest algorithm.

The project follows a structured and reproducible machine learning workflow, covering data exploration, preprocessing, feature engineering, model development, evaluation, hyperparameter optimization, and Kaggle submission.

## Objectives

- Explore and understand the Titanic passenger dataset.
- Identify patterns and factors associated with passenger survival.
- Develop a robust preprocessing and feature engineering pipeline.
- Train and evaluate a Random Forest classifier.
- Apply stratified cross-validation and hyperparameter optimization.
- Analyze feature importance using impurity-based and permutation-based methods.
- Generate predictions for the unseen test dataset and prepare a Kaggle submission.

## Machine Learning Workflow

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Missing value analysis and preprocessing
4. Feature engineering and categorical encoding
5. Random Forest model development
6. Model evaluation and classification metrics
7. Stratified cross-validation
8. Hyperparameter optimization using RandomizedSearchCV
9. Feature importance analysis
10. Final model training and Kaggle submission

## Model Performance

The optimized Random Forest model achieved the following results:

| Metric | Result |
|---|---:|
| Validation Accuracy | 83.24% |
| Cross-validation Accuracy | 83.17% |
| Best Cross-validation Accuracy | 84.96% |
| Validation Precision | 78.26% |
| Validation Recall | 78.26% |
| Validation F1-Score | 78.26% |

*Note: These results represent different evaluation stages and should not be interpreted as the same measurement.*

## Feature Importance

Permutation importance identified the following leading predictors:

| Feature | Importance |
|---|---:|
| Title | 0.206518 |
| Pclass | 0.097579 |
| Fare | 0.047858 |
| Age | 0.043203 |
| Sex | 0.028305 |
| FamilySize | 0.025885 |

Title was the strongest predictor according to the permutation importance analysis.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Kaggle

## Repository Structure

```text
titanic-survival-prediction/
│
├── titanic-survival-prediction-using-random-forest.ipynb
└── README.md
```

## Kaggle Submission

The optimized Random Forest pipeline was retrained using the complete labeled training dataset. Predictions were generated for the unseen test dataset and formatted into the required Kaggle submission structure.

## Author

**Rigan Collins Odero**

Software & AI Technology Specialist | Machine Learning | Data Science

GitHub: [@yengajr](https://github.com/yengajr)

---

*This project demonstrates an end-to-end supervised machine learning workflow using the Titanic survival prediction problem.*
