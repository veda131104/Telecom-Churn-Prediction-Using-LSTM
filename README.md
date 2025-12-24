# Telecommunications Customer Retention using LSTM

## 📖 Introduction
Why do customers leave from one telecommunication company? This project explores that question by predicting "churn"—the moment a customer switches to a different phone company. 

Customer retention is a crucial factor for profitability in the telecom sector. High churn rates significantly impact a company’s bottom line, market share, brand reputation, and long-term growth. This project implements advanced predictive analysis using **Long Short-Term Memory (LSTM)** networks to capture complex temporal patterns in customer behavior that traditional models often overlook.

This repository contains the implementation of the research paper:  [![Paper](https://img.shields.io/badge/IEEE-Publication-blue)](https://doi.org/10.1109/ICDSNS62112.2024.10691038) **"Enhancing Telecommunications Customer Retention: A Deep Learning Approach Using LSTM for Predictive Churn Analysis"** (Published in ICDSNS 2024).



## 📊 Dataset Specifications
The model is trained and validated using the **Customer Churn Prediction 2020** dataset from [![Dataset](https://img.shields.io/badge/Kaggle-Dataset-orange)](https://www.kaggle.com/c/customer-churn-prediction-2020).

* **Total Training Samples:** 4,250
* **Total Testing Samples:** 750
* **Input Features:** 19 (Including usage minutes, service plans, and support calls)
* **Target:** 1 Boolean variable (`churn`)

| Feature Name | Type | Description |
| :--- | :--- | :--- |
| `state` | String | 2-letter code of the US state of residence |
| `account_length` | Numerical | Number of months with the current provider |
| `area_code` | String | 3-digit area code (e.g., "area_code_415") |
| `international_plan` | Binary | Whether the customer has an international plan (yes/no) |
| `voice_mail_plan` | Binary | Whether the customer has a voice mail plan (yes/no) |
| `number_vmail_messages`| Numerical | Total number of voice-mail messages |
| `total_day_minutes` | Numerical | Total minutes of daytime calls |
| `total_day_calls` | Numerical | Total number of daytime calls |
| `total_day_charge` | Numerical | Total charge of daytime calls |
| `total_eve_minutes` | Numerical | Total minutes of evening calls |
| `total_eve_calls` | Numerical | Total number of evening calls |
| `total_eve_charge` | Numerical | Total charge of evening calls |
| `total_night_minutes` | Numerical | Total minutes of night calls |
| `total_night_calls` | Numerical | Total number of night calls |
| `total_night_charge` | Numerical | Total charge of night calls |
| `total_intl_minutes` | Numerical | Total minutes of international calls |
| `total_intl_calls` | Numerical | Total number of international calls |
| `total_intl_charge` | Numerical | Total charge of international calls |
| `number_customer_service_calls` | Numerical | Number of calls made to customer service |

## 🧠 Model Architecture
<img width="1690" height="745" alt="image" src="https://github.com/user-attachments/assets/b1e6685f-d17e-493b-be84-0747b7a37f4c" />

## 📈 Performance Results
Accuracy Graph:

<img width="969" height="421" alt="image" src="https://github.com/user-attachments/assets/f3c327f7-8b61-4974-8304-983a0a6c6730" />

Loss Graph:

<img width="1000" height="465" alt="image" src="https://github.com/user-attachments/assets/2fbfd308-b18c-418e-91a7-746474f1960e" />

ROC Curve:

<img width="1274" height="744" alt="image" src="https://github.com/user-attachments/assets/40e7cad7-7c0b-4cfc-8be6-d62158ec72e2" />











