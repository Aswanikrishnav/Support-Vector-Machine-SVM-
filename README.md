# 🧠 Support Vector Machines (SVM) for Classification

This project demonstrates how to use **Support Vector Machines (SVMs)** for both **linear** and **non-linear classification**. It includes training, hyperparameter tuning, visualization, and cross-validation using the **Breast Cancer Dataset** from Scikit-learn.

---

##  Objectives

* Train SVM models with **linear** and **RBF kernels**
* Visualize decision boundaries in 2D
* Perform **hyperparameter tuning** (`C`, `gamma`) with GridSearchCV
* Evaluate performance with **cross-validation**

---

## 🛠️ Tools & Libraries

* **Python 3**
* Scikit-learn
* NumPy
* Matplotlib

---







##  Key Concepts

* **Linear SVM:** Finds a straight line (or hyperplane) to separate classes.
* **RBF SVM:** Uses the Radial Basis Function kernel to separate data with a curved boundary.
* **C (Regularization):** Controls how strictly the model avoids misclassification.
* **Gamma:** Defines how far the influence of a single training example reaches.

---

##  Results

* Example best parameters found:

  ```
  Best Parameters: {'C': 10, 'gamma': 0.1}
  Cross-validation accuracy: ~0.88
  ```
* This means the model correctly classifies ~88% of samples on average across folds.

---

## Visualization

The script plots decision boundaries for both **linear** and **RBF** kernels (only for 2D features).

---



