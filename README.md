# Credit Card Fraud Detection Project
This project focuses on detecting fraudulent credit card transactions using supervised machine learning models. Due to the highly imbalanced nature of the dataset, resampling techniques and appropriate evaluation metrics were applied.
  Dataset
- Source: Kaggle Credit Card Fraud Dataset
- Transactions: 284,807
- Fraud cases: 492
- Features: Time, Amount, and PCA-transformed variables (V1–V28)

  Methodology
1. Data Cleaning and Preprocessing
2. Feature Scaling (StandardScaler)
3. Train-Test Split (70/30, stratified)
4. Class Imbalance Handling using SMOTE
5. Model Training:
   - Logistic Regression
   - Random Forest
   - XGBoost
6. Model Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC

 Results

| Model | Accuracy | Precision | Recall | F1 |
|------|---------|-----------|--------|----|
| Logistic Regression | 97.7% | 6.3% | 87.8% | 0.12 |
| Random Forest | **99.95%** | **89.9%** | 78.4% | **0.84** |
| XGBoost | 99.6% | 28.1% | 83.8% | 0.42 |
<img width="509" height="391" alt="image" src="https://github.com/user-attachments/assets/1854681f-e1dc-4594-9c17-66c4249705db" />


 Conclusion
 
Random Forest achieved the best performance, offering a strong balance between precision and recall.
This makes it a reliable model for real-world fraud detection systems.

 Technologies
- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn
- XGBoost
- matplotlib, seaborn

 ## Dataset

The dataset is not included due to size constraints.
You can download it from:
[Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


