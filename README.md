# Telco Customer Churn Prediction (KNIME Workflow)

This project analyzes and predicts customer churn in a telecommunications company using a visual workflow built in [KNIME Analytics Platform](https://www.knime.com/). It uses customer data to build machine learning models that can help identify customers likely to leave the service.

---

## Project Overview

- **Goal:** Predict whether a customer will churn (leave the company).
- **Tool Used:** KNIME 
- **Dataset:** Telco Customer Churn dataset (from Kaggle)

---

## Features

- Data Import and Exploration
- Data Cleaning and Preprocessing
- Machine Learning Model Training (e.g., Decision Tree, Random Forest)
- Model Evaluation with Accuracy, Precision, Recall, and AUC
- Export of predictions or reports
- Insights into which factors influence churn

---

## Workflow Structure

1. **Read Data**: Load customer dataset (CSV)
2. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical columns
   - Normalize/scale features
3. **Model Training**:
   - Train classification models
   - Perform cross-validation
4. **Model Evaluation**:
   - Accuracy, F1-score, ROC Curve
5. **Prediction and Export**:
   - Predict churn on test data
   - Export results

---

## Getting Started

### Requirements

- KNIME Analytics Platform (Version 4.7 or later recommended)  
  Download: https://www.knime.com/downloads

### Installation

- Clone or download this repository
- Open KNIME → File → Import KNIME Workflow → Select `Telco churn.knwf`


---

## Sample Output

- Confusion Matrix
- ROC Curve
- Feature Importance Charts

