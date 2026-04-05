# Wine Quality Classification using Support Vector Machine (SVM)

## 📌 Project Overview

This project uses **Support Vector Machine (SVM)** to classify wine quality into **Good** or **Bad** categories.

The dataset contains physicochemical properties of wine such as:

* Acidity
* Sugar
* pH
* Alcohol content
* Sulphates
* Density

The goal is to predict wine quality using different SVM kernels and compare their performance.

---

## ⚙️ Workflow

1. Load dataset
2. Data preprocessing

   * Remove unnecessary columns
   * Convert quality into binary labels
3. Feature scaling using StandardScaler
4. Train-test split
5. Train SVM models using:

   * Linear Kernel
   * Polynomial Kernel
   * RBF Kernel
6. Evaluate models using:

   * Accuracy
   * Confusion Matrix
   * Classification Report
7. Compare kernels based on performance

---

## 📊 Key Insights

* Linear kernel performs poorly due to class imbalance
* Polynomial kernel captures non-linear patterns better
* RBF kernel also performs well but slightly less effective than polynomial
* Polynomial kernel gives the best performance for this dataset

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python svm_wine_quality.py
```

---

## 📁 Dataset

`WineQT.csv`

---

## 👨‍💻 Purpose

This project demonstrates classification using SVM and compares different kernels to identify the best model for non-linear data.
