Support Vector Machine (SVM) Kernel Comparison Tutorial
Overview
This tutorial explores the use of Support Vector Machines (SVMs) with three different kernels — Linear, Polynomial, and RBF (Radial Basis Function) — to classify a synthetic dataset. The tutorial demonstrates how kernel choice impacts model performance and decision boundaries. It is designed to help readers understand the theoretical underpinnings of SVM kernels and their practical applications using Python.

Contents
Introduction: Overview of SVM and kernel functions.
Dataset: Synthetic dataset generated using make_classification with added noise for realism.
Implementation: Training and evaluating SVM models using three kernels.
Results: Comparison of accuracies and confusion matrices for each kernel.

Installation
Prerequisites
Python (≥ 3.8)
Jupyter Notebook or any Python IDE
Required Python libraries:
scikit-learn
numpy
matplotlib
seaborn
Setup


Navigate to the project directory:

download svm_tutorial_notebook.ipynb

Open the Jupyter Notebook:

open file 'svm_tutorial_notebook.ipynb' in Jupyter Notebook
Run the cells in sequence to:

Generate and visualize the dataset.
Train SVM models using different kernels.
Evaluate performance and visualize results.
Explore the code comments and explanations to understand each step.

Key Results
Accuracies
Kernel	Accuracy
Linear	80.00%
Polynomial	80.00%
RBF	76.67%
Confusion Matrices
Linear Kernel:
[[14  3]
 [ 3 10]]
Polynomial Kernel:
[[14  3]
 [ 3 10]]
RBF Kernel:
[[14  3]
 [ 4  9]]
Folder Structure
SVM-Kernel-Tutorial/
├── svm_tutorial.ipynb  # Jupyter Notebook tutorial
├── README.md                    # Project documentation
└── svm_tutorial.pdf             # PDF Tutorial also contains generated plots

Features
Comparison of SVM kernels on a synthetic dataset.
Detailed code with explanations for beginner-friendly learning.
Visualizations to illustrate performance and decision boundaries.
References
Cortes, C., & Vapnik, V. (1995). Support-vector networks. Machine Learning, 20(3), 273–297.
Pedregosa, F., et al. (2011). Scikit-learn: Machine Learning in Python. Journal of Machine Learning Research, 12, 2825–2830.
Scikit-learn documentation: https://scikit-learn.org



