# Breast Cancer Classification

I used this mini project to compare a few classifiers on scikit-learn's breast cancer dataset while keeping the feature checks and model evaluation leakage-safe.

## Dataset

The notebook uses `sklearn.datasets.load_breast_cancer`, so I did not copy a CSV into the repository.

## Structure

- `codes/Classification.ipynb` keeps the executed notebook with feature ranking, cross-validation, and the final holdout check.

## Method

I keep a stratified 80/20 split, inspect feature signal on the training split only with ANOVA and random-forest importance, and then compare logistic regression, a calibrated SVM, LDA, naive Bayes, decision tree, random forest, and bagging with 5-fold cross-validation.

## Run

Install `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `jupyter`, then open `codes/Classification.ipynb` from the project root.

## Evaluation

I track cross-validation accuracy, balanced accuracy, precision, recall, F1, and ROC AUC on the training split first. In the saved run, logistic regression finished first on the holdout split with accuracy `0.982` and ROC AUC `0.995`, while the calibrated SVM stayed very close.

## Limits

This dataset is small and already fairly clean, so the notebook is more useful for studying model comparison than for proving a deployment-ready pipeline. I also only keep one holdout split, so the final ranking can still move a little with a different random seed.
