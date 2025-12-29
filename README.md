#  Spam Email Classification using Machine Learning

This repository contains a beginner-friendly machine learning project that classifies emails as **spam** or **not spam** using classical ML techniques.

The project focuses on understanding the **end-to-end ML workflow**—from data loading to model training and evaluation—using clean and reproducible code practices.

---

## Project Overview

Spam detection is a binary classification problem.  
In this project, a machine learning model is trained on numerical features extracted from email content to predict whether an email is spam.

A **scikit-learn Pipeline** is used to keep preprocessing and modeling clean, modular, and reproducible.

---

## Tech Stack

- Python  
- NumPy  
- Pandas  
- scikit-learn  

---

##  Repository Structure
``` bash
├── Data/
│ └── spam.csv
├── Notebook/
│ └── email_spam.ipynb
├── README.md
└── requirements.txt
```

---

## Model Details

- **Model:** Logistic Regression  
- **Approach:**  
  - Train–test split  
  - Pipeline-based modeling  
  - Proper evaluation using multiple metrics  

This model serves as a strong baseline for spam email classification.

---

## Evaluation Metrics

The model is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

This avoids relying on accuracy alone, which is important for imbalanced classification problems like spam detection.

---

## How to Run

1. Clone the repository  
2. Install dependencies:
---
```
pip install -r requirements.txt
```
