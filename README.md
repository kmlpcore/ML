# 🩺 Diabetes Prediction System.

## 📌 Overview

This project implements a Machine Learning model to predict whether a patient is likely to have diabetes based on medical diagnostic features. The system uses Logistic Regression, a widely used classification algorithm, to provide accurate and interpretable predictions.

---

## 🎯 Problem Statement

Diabetes is a chronic disease that can lead to serious health complications if not detected early. The objective of this project is to build a predictive model that can classify patients as diabetic or non-diabetic based on input health parameters.

---

## 📊 Dataset

* **Source:** Pima Indians Diabetes Dataset
* **Features:**

  * Pregnancies
  * Glucose Level
  * Blood Pressure
  * Skin Thickness
  * Insulin
  * BMI
  * Diabetes Pedigree Function
  * Age
* **Target Variable:** Outcome (0 = Non-diabetic, 1 = Diabetic)

---

## 🧹 Data Preprocessing

* Handled missing or zero values in critical columns
* Feature scaling using StandardScaler
* Data normalization for improved model performance
* Dataset split into training and testing sets (80:20)

---

## 🤖 Model Building

* **Algorithm Used:** Logistic Regression
* **Why Logistic Regression?**

  * Suitable for binary classification problems
  * Fast and computationally efficient
  * Provides probabilistic output
  * Easy to interpret coefficients

---

## 🧪 Training & Testing

* Model trained on training dataset
* Evaluated using test dataset
* Performance metrics used:

  * Accuracy Score
  * Confusion Matrix
  * Precision & Recall

---

## 📈 Results

* **Accuracy:** ~75% (depending on preprocessing and tuning)
* Model shows reliable performance in predicting diabetic cases
* Balanced trade-off between precision and recall

---

## 🧠 Conclusion

The Logistic Regression model successfully predicts the likelihood of diabetes based on patient data. While the performance is satisfactory, further improvements can be achieved using advanced models and hyperparameter tuning.

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn
* Dash (for interactive dashboard visualization)

Install dependencies using:
pip install -r requirements.txt

---

## 🙌 Acknowledgment

This project was developed as part of an academic mini project to demonstrate practical implementation of machine learning in healthcare prediction systems.

---
