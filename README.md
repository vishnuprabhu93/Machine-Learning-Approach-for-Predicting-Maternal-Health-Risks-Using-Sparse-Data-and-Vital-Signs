# Maternal Health Risk Prediction Using Machine Learning

[![DOI](https://img.shields.io/badge/DOI-10.3390%2Ffi17050190-blue)](https://doi.org/10.3390/fi17050190)

This repository contains the codebook and supporting materials for the research article:

**“A Machine Learning Approach for Predicting Maternal Health Risks in Lower-Middle-Income Countries Using Sparse Data and Vital Signs”**  
Published in *Future Internet*, April 2025  
Authors: Avnish Malde, Vishnunarayan Girishan Prabhu, Dishant Banga, Michael Hsieh, Chaithanya Renduchintala, Ronald Pirrallo

🔗 [Read the paper](https://doi.org/10.3390/fi17050190)

---

## 🧠 Summary

This project explores the use of machine learning to predict maternal health risks using sparse data collected from 1,014 pregnant women in rural Bangladesh. The models utilize basic vitals—such as age, blood pressure, heart rate, and blood glucose—to classify maternal health risk into three categories: **low**, **mid**, and **high**.

**Key contributions include:**

- A comparison of multiple machine learning classifiers including CatBoost, XGBoost, Random Forest, and Decision Tree.
- A **stacking ensemble model with stratified sampling**, achieving the highest accuracy of **87.2%**.
- Demonstrating how limited clinical data can be used effectively in resource-limited settings.

---


---

## 📊 Dataset Overview

The dataset includes anonymized health data from 1,014 pregnant women with the following features:

- **Age**
- **Blood Pressure**
- **Temperature**
- **Heart Rate**
- **Blood Glucose**
- **Risk Label**: `low`, `mid`, `high`

---

## 🚀 Getting Started

### Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- catboost
- matplotlib
- seaborn
- jupyter (optional)


Malde, A.; Prabhu, V.G.; Banga, D.; Hsieh, M.; Renduchintala, C.; Pirrallo, R. 
A Machine Learning Approach for Predicting Maternal Health Risks in Lower-Middle-Income Countries Using Sparse Data and Vital Signs. 
Future Internet 2025, 17, 190. https://doi.org/10.3390/fi17050190
