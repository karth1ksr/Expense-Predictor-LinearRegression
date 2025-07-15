# Project: Medical Cost Prediction using Linear Regression

## Files
- insurance_predictor.ipynb : Jupyter notebook containing all steps of the regression project
- insurance.csv                     : Dataset with demographic and medical cost information
Data Source - Kaggle [Insurance Csv](https://www.kaggle.com/datasets/awaiskaggler/insurance-csv)

## Objective
Predict individual medical insurance charges based on demographic factors using a Linear Regression model.

## Dataset Description (`insurance.csv`)
Contains 1,300+ rows with the following columns:
- `age`: Age of primary beneficiary
- `sex`: Gender (male/female)
- `bmi`: Body Mass Index
- `children`: Number of dependents covered
- `smoker`: Smoking status (yes/no)
- `region`: Residential area (northeast, southeast, etc.)
- `charges`: Actual medical insurance charges (target variable)

## Key Steps in Notebook
1. Load and explore the dataset
2. Handle categorical variables (OneHotEncoding for `sex`, `smoker`, and `region`)
3. Visualize correlations with `charges`
4. Split data into training and testing sets
5. Train a Linear Regression model using scikit-learn
6. Evaluate model performance (R² score, RMSE)
7. Predict charges on test data

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

To install all dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## How to Run
1. Open insurance_linear_regression.ipynb in Jupyter Notebook or VS Code

2. Ensure insurance.csv is in the same directory

3. Run all cells sequentially to view EDA, training process, and evaluation metrics

## Output
1. Regression coefficients and intercept

2. Performance metrics: R² Score, RMSE
