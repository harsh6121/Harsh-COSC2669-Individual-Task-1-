# COSC2669 Individual Task 1

## Case Study

**Commercial Data Analyst - Coles Group**

This repository contains the machine learning analysis completed for Individual Task 1.

The analysis uses two retail datasets and compares Logistic Regression and Random Forest for two different classification tasks.

---

## Datasets

### 1. Online Retail II
Source:  
https://archive.ics.uci.edu/dataset/502/online+retail+ii

This dataset contains retail transaction history and is used to analyse whether historical customer behaviour can help identify future high-value customers.

### 2. Online Shoppers Purchasing Intention
Source:  
https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

This dataset contains website browsing-session information and is used to predict whether a session results in a purchase.

The raw datasets are not included in this repository because of their file size. They can be downloaded directly from the original UCI Machine Learning Repository links above.

---

## Machine Learning Models

Two classification algorithms were evaluated:

- Logistic Regression
- Random Forest

---

## Evaluation Metrics

The models were compared using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

Feature importance from Random Forest was also examined to identify important predictors.

---

## Repository Structure

```text
COSC2669-Individual-Task-1/
├── Coles_Commercial_Data_Analyst_Part1_3.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── README.md
└── figures/
    ├── retail_feature_importance.png
    ├── shoppers_feature_importance.png
    ├── retail_confusion_matrix.png
    └── shoppers_confusion_matrix.png
