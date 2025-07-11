# 🎓 Student Performance Predictor

A machine learning project designed to help predict student academic performance based on various personal and academic factors. By analyzing data such as study time, absences, and family support, this project provides an intelligent prediction model to assess a student's final grade.

---

## 📌 Project Overview

This project walks through the complete process of:

* Exploring and understanding student data
* Preprocessing and selecting relevant features
* Building and training machine learning models
* Evaluating model performance
* Making final predictions using the best model

The goal is to help educators, institutions, and students themselves identify patterns that may impact academic success.

---

## 🚀 Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas, NumPy** – for data manipulation
* **Matplotlib, Seaborn** – for data visualization
* **Scikit-learn** – for building machine learning models

---

## 📊 Features Considered

We used a mix of academic, behavioral, and family-related features including:

* `studytime`, `failures`, `absences`, `schoolsup`, `famsup`
* `goout`, `health`, `internet`, `romantic`, etc.
* The target variable is `G3` (final grade), used for prediction.

---

## 🧠 Model Building & Results

After trying out different machine learning models, the **Random Forest Regressor** gave the best results.

### ✅ Final Model: Random Forest Regressor

* **R² Score**: 0.823
* **Mean Squared Error**: 3.62
* **Mean Absolute Error**: 1.13
* **Approximate Accuracy**: **89.46%**

This means the model can predict the student's final performance with high reliability based on historical data.



