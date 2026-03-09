# ❤️ Heart Disease Prediction

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-1.x-orange?style=flat-square&logo=scikitlearn)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.x-white?style=flat-square&logo=pandas)](https://pandas.pydata.org/)
[![Colab](https://img.shields.io/badge/Open_In-Colab-yellow?style=flat-square&logo=googlecolab)](https://colab.research.google.com/github/PRAGALATHANC/Heart-Disease-Prediction/blob/main/HeartDiseasePredictonUsingML.ipynb)

A machine learning-based diagnostic tool designed to predict the presence of heart disease in patients based on clinical parameters. The project utilizes a **Logistic Regression** model to classify hearts as "Healthy" or "Defective" with high accuracy.

---

## 📖 Overview

This project focuses on the collection and processing of medical data to build a predictive system. By analyzing various health metrics, the model can assist healthcare professionals in early detection and risk assessment of cardiovascular issues.

### Key Features
* 📊 **Data Processing:** Robust handling of clinical datasets using `Pandas` and `NumPy`.
* 🧠 **Machine Learning:** Implementation of **Logistic Regression** for binary classification.
* 🎯 **Evaluation Metrics:** Accuracy scoring for both training and test datasets to ensure model reliability.
* 🚀 **Predictive System:** A dedicated module that takes raw clinical input and returns a real-time health diagnosis.

---

## 🏗️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Language** | Python 3 |
| **Libraries** | Scikit-Learn, Pandas, NumPy |
| **Model** | Logistic Regression |
| **Environment** | Google Colab / Jupyter Notebook |

---

## 🗂️ Workflow

1.  **Data Collection:** Loading patient data from `heart.csv`.
2.  **Preprocessing:** Checking for missing values and analyzing the distribution of the target variable.
3.  **Train-Test Split:** Splitting data into an 80/20 ratio while maintaining class stratification.
4.  **Model Training:** Training the Logistic Regression engine on clinical features.
5.  **Prediction:** Testing the system with new, unseen clinical instances.

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have the following Python libraries installed:
```bash
pip install numpy pandas scikit-learn
