# Learning Process

I used these notebooks as my running notes while studying the main ideas from the course and book. I kept the saved outputs so I can quickly remember what each result looked like when I first got it working.

## Topics

- [ML_Overview.ipynb](./ML_Overview.ipynb) covers my first pass through NumPy, pandas, plotting, and a simple KNN classifier.
- [One_Hot_Encoding.ipynb](./One_Hot_Encoding.ipynb) is where I practiced turning categories into model-ready columns.
- [Linear_Regression.ipynb](./Linear_Regression.ipynb) and [Regularization_methods.ipynb](./Regularization_methods.ipynb) track how I studied linear models, overfitting, ridge, and lasso.
- [Logistic_Regression.ipynb](./Logistic_Regression.ipynb), [KNN_test.ipynb](./KNN_test.ipynb), [KNN_regression.ipynb](./KNN_regression.ipynb), and [SVM.ipynb](./SVM.ipynb) cover the core supervised models I practiced first.
- [Univariate_statistics.ipynb](./Univariate_statistics.ipynb), [Iterative_selection.ipynb](./Iterative_selection.ipynb), and [Model_based_selection.ipynb](./Model_based_selection.ipynb) are my feature-selection notes.
- [PCA.ipynb](./PCA.ipynb) is where I studied dimensionality reduction and how PCA changes both visualization and classification.

## Structure

All of the course learning notebooks live in this folder. Larger applied projects stay in their own top-level repository folders.

## Setup

I ran these notebooks with Python 3.12. The main packages I needed were `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `jupyter`, and `nbformat`.

## Running

Start Jupyter from the repository root or from this folder, then open any notebook here. Most notebooks use built-in scikit-learn datasets, so they should run without extra downloads.

## What I learned

Keeping these notebooks together makes the progression clearer for me: preprocessing first, then models, then feature selection and PCA. The saved outputs are useful because I can compare later project results against these smaller study cases.
