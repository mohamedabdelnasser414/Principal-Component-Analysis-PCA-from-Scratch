Principal Component Analysis (PCA) from Scratch

This repository contains an implementation of Principal Component Analysis (PCA) built from first principles, using only basic numerical and plotting libraries.
No high-level machine learning or statistics libraries (e.g. scikit-learn, SciPy, TensorFlow, PyTorch) are used.

The goal of this project is to develop a mathematical and practical understanding of PCA by implementing each step explicitly.

📌 Project Overview

Principal Component Analysis (PCA) is a dimensionality reduction technique used to transform high-dimensional, correlated data into a smaller set of uncorrelated variables (principal components) while preserving most of the variance.

This project demonstrates:

how PCA works mathematically,

how variance is distributed across principal components,

and how high-dimensional data can be visualised in lower dimensions.

📊 Dataset

The project uses the Wheat Seeds dataset, which contains physical measurements of wheat kernels, including:

Area

Perimeter

Kernel length

Kernel width

Compactness

Asymmetry coefficient

Groove length

These features are highly correlated, making the dataset well-suited for dimensionality reduction using PCA.

🛠️ Methods & Implementation

PCA is implemented step-by-step using linear algebra:

Mean-centering the data

Computing the covariance matrix

Performing eigenvalue–eigenvector decomposition

Sorting components by explained variance

Constructing a projection matrix

Projecting the data into a lower-dimensional space

The dataset is reduced from 7 dimensions to 2 dimensions for visualization.

📈 Results

Most of the variance is captured by the first few principal components

Later components have near-zero variance, indicating strong feature redundancy

The 2D projection preserves the essential structure of the dataset

This confirms that PCA effectively reduces dimensionality while retaining important information.

🎓 Learning Outcomes

Through this project, I gained a deeper understanding of:

The geometric interpretation of PCA

The role of eigenvalues and eigenvectors in variance analysis

The importance of data centering

The difference between projection and reconstruction

Implementing core ML techniques without relying on black-box libraries

🧰 Libraries Used

Python

NumPy

Matplotlib

(No ML or statistics libraries were used.)

📁 Repository Contents

PCA Wheat Seeds dataset.ipynb — Jupyter notebook containing the full implementation and analysis

seeds_dataset.csv — Dataset used for the project
