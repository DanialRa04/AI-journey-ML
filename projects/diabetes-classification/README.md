# Diabetes Classification

I used this mini project to compare standard classifiers on the Pima diabetes dataset with a clear train/test split and reusable repo-local data path.

## Dataset

The notebook uses `data/diabetes.csv`, the same source table already used by the glucose regression project. The target is `Outcome`, where `1` marks diabetes and `0` marks no diabetes.

## Structure

- `codes/Diabetes_Classification.ipynb` keeps the cleaned classifier comparison notebook.
- `data/diabetes.csv` is the source CSV used by the notebook.

## Method

The notebook checks the feature distributions and class balance, splits the data into training and test sets, scales the predictors, and compares decision tree, naive Bayes, SVM, LDA, random forest, logistic regression, and bagging classifiers.

## Run

Install `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `jupyter`, then open `codes/Diabetes_Classification.ipynb` from the project folder. The saved dataset path points to `../data/diabetes.csv`.

## Limits

This is a course-style classifier comparison on a small dataset. I would use the confusion matrices and class-level metrics instead of relying only on accuracy.
