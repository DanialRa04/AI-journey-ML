# ML Fundamentals

I used these notebooks as running notes while studying the main ideas from the course and book. I kept the saved outputs where they help me remember what each result looked like.

## Topics

- [ML_Overview.ipynb](./codes/ML_Overview.ipynb) covers my first pass through NumPy, pandas, plotting, and a simple KNN classifier.
- [One_Hot_Encoding.ipynb](./codes/One_Hot_Encoding.ipynb) is where I practiced turning categories into model-ready columns.
- [Linear_Regression.ipynb](./codes/Linear_Regression.ipynb) and [Regularization_methods.ipynb](./codes/Regularization_methods.ipynb) track how I studied linear models, overfitting, ridge, and lasso.
- [Logistic_Regression.ipynb](./codes/Logistic_Regression.ipynb), [KNN_test.ipynb](./codes/KNN_test.ipynb), [KNN_regression.ipynb](./codes/KNN_regression.ipynb), and [SVM.ipynb](./codes/SVM.ipynb) cover the core supervised models I practiced first.
- [Univariate_statistics.ipynb](./codes/Univariate_statistics.ipynb), [Iterative_selection.ipynb](./codes/Iterative_selection.ipynb), and [Model_based_selection.ipynb](./codes/Model_based_selection.ipynb) are my feature-selection notes.
- [PCA.ipynb](./codes/PCA.ipynb) is where I studied dimensionality reduction and how PCA changes both visualization and classification.
- [Data_Cleaning_Basics.ipynb](./codes/Data_Cleaning_Basics.ipynb) covers outliers, missing values, imputation, and simple cleaning checks.
- [ML_Intro_Packages_KNN.ipynb](./codes/ML_Intro_Packages_KNN.ipynb) is an intro notebook for NumPy, SciPy, pandas, plotting, and a first KNN classifier.
- [Feature_Selection_Breast_Cancer.ipynb](./codes/Feature_Selection_Breast_Cancer.ipynb) compares feature selection and dimensionality reduction methods on the breast cancer dataset.
- [KMeans_Initialization.ipynb](./codes/KMeans_Initialization.ipynb) shows how K-Means behaves with different starting centers.
- [Neural_Network_Hyperparameters.ipynb](./codes/Neural_Network_Hyperparameters.ipynb) compares simple TensorFlow regression networks with different widths and activations.

## Structure

All course and study notebooks live in `codes/`.

## Setup

I ran these notebooks with Python 3.12. The main packages I needed were `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`, `jupyter`, and `nbformat`. The neural-network hyperparameter notebook also needs `tensorflow`.

## Running

Start Jupyter from the repository root and open any notebook in `codes/`. Many notebooks use built-in scikit-learn datasets, but `One_Hot_Encoding.ipynb` downloads the Adult dataset from OpenML and `KNN_regression.ipynb` plus `SVM.ipynb` download the California housing dataset on first run.
