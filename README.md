# AI Journey: Machine Learning

I keep my ML fundamentals and mini projects here in one place. The fundamentals stay together, and the applied work lives under `projects/` so the repo is easier to scan.

## Repository map

- [fundamentals/README.md](./fundamentals/README.md) for the study-note codes
- [projects/diabetes-glucose-regression/README.md](./projects/diabetes-glucose-regression/README.md) for the glucose regression mini project
- [projects/diabetes-classification/README.md](./projects/diabetes-classification/README.md) for the diabetes classifier comparison
- [projects/neural-activity-regression/README.md](./projects/neural-activity-regression/README.md) for the neural activity regression study
- [projects/breast-cancer-classification/README.md](./projects/breast-cancer-classification/README.md) for the breast cancer classification mini project
- [projects/heart-disease-ann/README.md](./projects/heart-disease-ann/README.md) for the multiclass ANN project
- [projects/lumpy-skin-disease-classification/README.md](./projects/lumpy-skin-disease-classification/README.md) for the lumpy skin disease classification project

## Structure

- `fundamentals/codes/` keeps the executed course notebooks.
- `projects/*/codes/` keeps each project notebook.
- `projects/*/data/` keeps only the datasets needed to rerun those notebooks.

## Setup

Most notebooks need `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, and `jupyter`. A few fundamentals notebooks download public datasets on first run, and the neural activity project downloads a public `.npy` file into its local `data/` folder. The neural-network hyperparameter notebook also needs `tensorflow`.
