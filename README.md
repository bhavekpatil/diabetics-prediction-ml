# Machine Learning Project: Logistic Regression Classifier

## 📌 Overview

This project demonstrates a **Logistic Regression** model built from scratch using Python. The goal is to train a model on a dataset, evaluate its performance, and understand how linear models work.

The project includes:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Train–test split
* Model training with Logistic Regression
* Evaluation using **accuracy**, **precision**, **recall**, **F1-score**, **confusion matrix**, and **ROC curve**

---

## 📂 Project Structure

```
├── Logistic_Regression_Project.ipynb
├── README.md
```

---

## 🧠 Machine Learning Concepts Covered

### 1. Logistic Regression

* A classification algorithm used for binary outcomes.
* Based on the **sigmoid function**:

  $$\sigma(z) = \frac{1}{1 + e^{-z}}$$

### 2. Linear Equation

Logistic regression uses a **linear combination** of features:

$$z = w_1x_1 + w_2x_2 + \dots + b$$

### 3. Non‑Linear Data

Datasets that cannot be separated by a straight line.
Logistic Regression uses **decision boundaries**, but on non‑linear data performance may drop.

---

## 📊 Evaluation Metrics

* **Accuracy**
* **Precision**
* **Recall**
* **F1 Score**
* **Confusion Matrix**
* **ROC Curve & AUC**

These help measure the overall performance of the model beyond simple accuracy.

---

## 🔧 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit‑learn
* Google Colab

---

## ▶️ How to Run

1. Clone the repo:

```
git clone https://github.com/bhavekpatil/diabetic-predictipn-ml

```

2. Open the notebook in Jupyter/Google Colab.
3. Run all cells.

---

## ⭐ Results

Model performance on test data: 76% Accuracy

* **Confusion Matrix**:

```
[[62  8]
 [16 14]]
```

* **Accuracy**: 0.76
* **Precision**: 0.6363
* **Recall**: 0.4667
* **F1 Score**: 0.5385

---

## 📌 Future Improvements

* Add more ML models (SVM, Decision Tree, Neural Networks)
* Feature scaling & optimization
* Hyperparameter tuning
* Handle imbalanced data

---

## 🙌 Author

Bhavek Patil

* LinkedIn: https://www.linkedin.com/in/bhavek-patil-7016b9325
* GitHub:https://github.com/bhavekpatil

---

If you like this project, feel free to ⭐ star the repo and connect with me!

