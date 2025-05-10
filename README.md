# 🧬 Breast Cancer Diagnosis with PCA and Logistic Regression

This repository showcases using Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for classification, using the breast cancer dataset from `sklearn.datasets`.

## 📌 Project Overview

The goal of this project is to:

- Implement PCA using the cancer dataset from sklearn.datasets.

-  Reduce the dataset into 2 PCA components.

-  Optionally, implement logistic regression for prediction to earn bonus points.

-  Submit  work as a zipped file or a link to your GitHub repository. Include a README file with comprehensive instructions. 


---

## 📁 Dataset

- Breast cancer dataset from `sklearn.datasets.load_breast_cancer()`
- Features: 30 numeric features describing tumor characteristics.
- Target: Malignant (0) or Benign (1).

---

##  🚀 Getting Started
To get started, follow these steps:

Clone the repository (if applicable):

bash
git clone(https://github.com/techygurl/Principal-Component-Analysis-assigment)
cd your-repo-name
Launch Jupyter Notebook:



jupyter notebook
Open Milestone_Assignment_2.ipynb in your browser and run the notebook cell by cell.

---


##  Apply PCA:

python


from sklearn.decomposition import PCA

pca = PCA(n_components=2)
X_pca = pca.fit_transform(X_scaled)

---

##  Train Logistic Regression
python


logreg = LogisticRegression()
logreg.fit(X_train, y_train)

This creates a LogisticRegression model and trains it on the training data (X_train, y_train).


