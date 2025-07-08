# Logistic Regression Model for Predicting "Dore"

This project implements a logistic regression model to predict the occurrence of "Dore" based on age and gender data.

## Dataset
- The dataset contains 2594 rows with three columns: `age`, `gender`, and `dore`.
- Age is categorized into groups: 9-15, 16-30, 31-50, 51-70, 71-90.
- Gender values are encoded as 0 (female) and 1 (male).
- Target variable `dore` is binary: 0 (no), 1 (yes).

## Data Preprocessing
- Missing values are removed.
- Age is binned into categorical groups.
- Gender and target columns are encoded to numeric values.

## Model
- Logistic Regression from scikit-learn is used.
- The dataset is split into training (80%) and test (20%) sets.
- The model is trained on training data and tested on test data.

## Usage
1. Load the dataset (`gender_age_dore.csv`).
2. Run preprocessing steps to clean and encode data.
3. Train logistic regression model.
4. Predict on test data and evaluate performance.

## Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn

## Author
Faride Jafari


