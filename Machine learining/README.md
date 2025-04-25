# Machine Learning Evaluation for MOFA and MoGCN Features

This folder contains **Python Jupyter Notebooks** used to evaluate machine learning models based on features selected by **MOFA** (Multi-Omics Factor Analysis) and **MoGCN** (Multi-omics Graph Convolutional Network).

## 📜 Files

- **Evaluation of MOFA Selected Features.ipynb**  
  Evaluates features selected by MOFA using different classifiers.
  
- **(Evaluation of MoGCN Selected Features.ipynb)**  
  Evaluates features selected by MoGCN using the same set of classifiers.


## Objective

The main objectives of these notebooks are:
- To compare the predictive performance of MOFA-selected features vs. MoGCN-selected features.
- To evaluate multiple machine learning classifiers using cross-validation.
- To assess models based on metrics like **Accuracy**, **Precision**, **Recall**, **F1-score**, and **Confusion Matrix**.

## Requirements

- **Python** version 3.8 or higher
- **Jupyter Notebook** environment (or JupyterLab)

Install required Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
