# Principal Component Analysis (PCA) from Scratch

This repository contains an implementation of **Principal Component Analysis (PCA)** built **mathematically from first principles**, using only basic numerical and plotting libraries.  
No high-level machine learning or statistics libraries (such as scikit-learn, SciPy, TensorFlow, or PyTorch) are used.

The purpose of this project is to gain a **deep understanding of PCA** by implementing each step explicitly.

---

## 📌 Project Overview

Principal Component Analysis (PCA) is a **dimensionality reduction technique** that transforms high-dimensional, correlated data into a smaller set of uncorrelated components (principal components) while preserving most of the variance.

This project demonstrates:
- how PCA works mathematically,
- how variance is distributed across principal components,
- and how high-dimensional data can be visualized in lower dimensions.

---

## 📊 Dataset

The project uses the **Wheat Seeds dataset**, which contains physical measurements of wheat kernels, including:

- Area  
- Perimeter  
- Kernel length  
- Kernel width  
- Compactness  
- Asymmetry coefficient  
- Groove length  

These features are highly correlated, making the dataset well-suited for dimensionality reduction using PCA.

---

## 🛠️ Methods & Implementation

PCA is implemented step by step using linear algebra:

1. Mean-centering the dataset  
2. Computing the covariance matrix  
3. Performing eigenvalue–eigenvector decomposition  
4. Sorting principal components by explained variance  
5. Constructing a projection matrix  
6. Projecting the data into a lower-dimensional space  

The dataset is reduced from **7 dimensions to 2 dimensions** for visualization.

---

## 📈 Results

- The first few principal components capture nearly all of the variance  
- Later components have near-zero variance, indicating strong feature redundancy  
- The 2D projection preserves the essential structure of the dataset  

This confirms that PCA effectively reduces dimensionality while retaining important information.

<img width="778" height="494" alt="Screenshot 2026-01-12 at 14 24 53" src="https://github.com/user-attachments/assets/b5f6f66d-70fe-4c47-99a4-38b2a456ae63" />

<img width="839" height="593" alt="Screenshot 2026-01-12 at 14 25 08" src="https://github.com/user-attachments/assets/ee4c357c-fa50-40a4-a35b-0e1ff6187647" />

---

## 🎓 Learning Outcomes

This project strengthened my understanding of:

- The geometric interpretation of PCA  
- The role of eigenvalues and eigenvectors  
- Why data must be mean-centered  
- The difference between projection and reconstruction  
- Implementing ML fundamentals without black-box libraries  

---

## 🧰 Libraries Used

- Python  
- NumPy  
- Matplotlib  

*(No machine learning or statistics libraries were used.)*

---

## 📁 Repository Structure

