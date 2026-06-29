# Diabetes Glucose Regression

I used this mini project to predict glucose from the other Pima measurements while keeping the preprocessing leakage-safe.

## Dataset

The data comes from `Dataset/diabetes.csv`. I drop rows where `Glucose` is zero because that is not a usable regression target, and I treat zero values in `BloodPressure`, `SkinThickness`, `Insulin`, and `BMI` as missing measurements.

## Structure

- `Codes/Regression.ipynb` keeps the executed notebook with cleaning, model comparison, and diagnostics.
- `Dataset/diabetes.csv` is the source CSV used by the notebook.

## Method

I keep `Outcome` out of the predictors because it is too close to the glucose label. The notebook compares dummy, ridge, lasso, KNN, SVR, random forest, and histogram gradient boosting pipelines with 5-fold cross-validation on the training split.

## Run

Install `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `jupyter`, then run the notebook from the `Codes` folder so the relative dataset path works as saved.

## Evaluation

I track cross-validation RMSE, MAE, and R2 on the training split, then keep a final test split for the holdout check. In the saved run, lasso was the most stable model and beat the dummy baseline by a noticeable margin.

## Limits

This dataset is small, `Insulin` is heavily missing, and the test R2 is still modest. I would treat this as a study exercise, not a clinical tool.
