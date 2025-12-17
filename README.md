# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on building a **Heart Disease Prediction System** using machine learning techniques. The system analyzes patient clinical and diagnostic data to predict whether a person is likely to have heart disease. The goal is to compare multiple classification models and identify the best-performing and most reliable model using appropriate evaluation metrics.

This project is suitable for **academic purposes, resumes, interviews, and beginner-to-intermediate ML portfolios**.

---

## 🧠 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes. Using historical medical data, this project aims to predict the presence of heart disease based on patient attributes such as age, chest pain type, heart rate, and ECG-related features.

---

## 📊 Dataset Information

* **Dataset:** Heart Disease Dataset (UCI-style)
* **Number of Records:** 303
* **Number of Features:** 14
* **Target Variable:**

  * `1` → Heart Disease Present
  * `0` → No Heart Disease

### 🔑 Selected Important Features

* `age` – Age of the patient
* `sex` – Gender (1 = Male, 0 = Female)
* `cp` – Chest pain type
* `thalach` – Maximum heart rate achieved
* `oldpeak` – ST depression induced by exercise
* `slope` – Slope of the peak exercise ST segment
* `thal` – Thalassemia condition

---

## ⚙️ Project Workflow

1. Data Loading and Understanding
2. Data Cleaning and Preprocessing
3. Feature Selection
4. Train-Test Split
5. Handling Class Imbalance (SMOTE)
6. Model Training
7. Model Evaluation
8. ROC Curve Comparison
9. Final Model Selection

---

## 🤖 Machine Learning Models Used

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Tree Classifier
* Random Forest Classifier

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* ROC-AUC Score

### 🏆 Best Performing Model

* **Random Forest Classifier** showed the highest ROC-AUC score and overall performance.
* **Logistic Regression** performed consistently well and is preferred for interpretability in medical applications.

---

## 📉 ROC Curve Analysis

ROC curves were plotted for all models to visually compare performance. The model with the curve closest to the top-left corner and the highest AUC was selected as the best model.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## 📌 Key Learnings

* End-to-end ML project workflow
* Handling imbalanced datasets using SMOTE
* Comparing multiple classification models
* ROC-AUC based model evaluation
* Logging and debugging ML pipelines

---

## 📄 Conclusion

This project demonstrates how machine learning can be effectively used for early detection of heart disease. By comparing multiple models, Random Forest was identified as the best-performing model, while Logistic Regression offered better interpretability. The project highlights the importance of data preprocessing, evaluation metrics, and model selection in real-world ML applications.


