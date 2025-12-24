# Telecommunications Customer Retention using LSTM

## 📖 Introduction
Why do customers leave from one telecommunication company? This project explores that question by predicting "churn"—the moment a customer switches to a different phone company. 

Customer retention is a crucial factor for profitability in the telecom sector. High churn rates significantly impact a company’s bottom line, market share, brand reputation, and long-term growth. This project implements advanced predictive analysis using **Long Short-Term Memory (LSTM)** networks to capture complex temporal patterns in customer behavior that traditional models often overlook.

This repository contains the implementation of the research paper:  
[![Paper](https://img.shields.io/badge/IEEE-Publication-blue)](https://doi.org/10.1109/ICDSNS62112.2024.10691038) **"Enhancing Telecommunications Customer Retention: A Deep Learning Approach Using LSTM for Predictive Churn Analysis"** (Published in ICDSNS 2024).



## 📊 Dataset Specifications
The model is trained and validated using the **Customer Churn Prediction 2020** dataset from [![Dataset](https://img.shields.io/badge/Kaggle-Dataset-orange)](https://www.kaggle.com/c/customer-churn-prediction-2020).

* **Total Training Samples:** 4,250
* **Total Testing Samples:** 750
* **Input Features:** 19 (Including usage minutes, service plans, and support calls)
* **Target:** 1 Boolean variable (`churn`)

| Feature Category | Data Points |
| :--- | :--- |
| **Service Plans** | International Plan, Voice Mail Plan |
| **Activity Metrics** | Day/Evening/Night/Intl Minutes, Calls, and Charges |
| **Customer Support** | Customer Service Calls |
| **Account Info** | Account Length, State, Area Code |









