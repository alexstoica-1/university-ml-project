# University Deep Learning Project

This repository contains my university project work for practicing and applying deep learning methods.  
The main code and experiments are in Jupyter notebooks, and the project task is described below.

---

## Project Task (Summary)
The initial task was to:
- Work with a given dataset in `mldata_0003260547`.
- Understand and analyze the provided data structure and features.
- Build, train, and evaluate deep learning models to solve the problem defined by the dataset.
- Compare different approaches and document observations.

---

## Contents
- `notebook.ipynb` – main notebook with data exploration, preprocessing, model training, and evaluation.

---

## Features
- Data loading and preprocessing
- Exploratory data analysis
- Neural network implementation
- Training and evaluation of models
- Documentation of results and findings

---

## Conclusions
- Both algorithms (KNN and Random Forest) were tuned for their key hyperparameters:
  - KNN: number of neighbors (k), distance metric, weighting strategy.
  - Random Forest: number of trees, maximum depth, and split criteria.

- The results showed that:
  - Random Forest consistently outperformed KNN in accuracy and stability across cross-validation folds.
  - KNN performed reasonably well for small k values, but was sensitive to parameter changes and less robust.

- Final Choice:
  - The Random Forest model with optimized hyperparameters (e.g., ~100 trees, balanced depth) was chosen as the best model.
  - It achieved the highest accuracy and offered better generalization for this dataset.

---

## Requirements
- Python 3.9+
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter

Install them with:
```bash
pip install -r requirements.txt
