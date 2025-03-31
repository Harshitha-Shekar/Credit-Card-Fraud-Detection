# Credit Card Fraud Detection  
**Detecting fraudulent transactions using Machine Learning**  

## Overview  
This project analyzes a dataset of credit card transactions and applies machine learning models to detect fraud.  

## Models Used  
1. **Logistic Regression** – Simple but biased towards non-fraudulent transactions.  
2. **Random Forest** – Handles nonlinearity and improves fraud detection.  
3. **XGBoost** – Best model, balancing fraud detection and accuracy.  

## Training & Evaluation  
- **Dataset Split:** 80% Train | 20% Test  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score  
- **Best Model:** XGBoost (F1 Score: 0.72)  

## Results Summary  
| Model               | Accuracy | Precision (Fraud) | Recall (Fraud) | F1 Score |
|---------------------|----------|------------------|---------------|----------|
| Logistic Regression | 99%      | 0.00            | 0.00          | 0.00     |
| Random Forest      | 100%     | 0.91            | 0.40          | 0.56     |
| XGBoost           | Best    | Balanced       | Higher Recall | 0.72     |

## Files in Repository  
- `3S_ML_CAC -2 Team Project.ipynb` - Jupyter Notebook with code  
- `Team-D_ML_CAC2_Report.pdf` - Project report  
- `README.md` - Project details  

## 🔗 References  
Dataset sourced from Kaggle.  
https://www.kaggle.com/datasets/tusharbhadouria/credit-card-fraud-detection
