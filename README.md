# Bank-Marketing-Prediction
Predicting Customer Subscription to Term Deposit Campaigns Using Machine Learning
# Bank Marketing Subscription Prediction

## Dataset : https://archive.ics.uci.edu/dataset/222/bank+marketing
- Source: UCI Machine Learning Repository
- 41,188 records → sampled to 12,356 for analysis
- Features include customer demographics, contact method, campaign details, and economic indicators.

---

## Methods
- Data cleaning: Handling unknowns, outliers, and duplicates
- Feature engineering: Creating new indicators
- Preprocessing: Standardization, one-hot encoding
- Imbalanced data handling: SMOTE
- Model building: Logistic Regression, SVM, Random Forest, Decision Tree, Naive Bayes
- Hyperparameter tuning: GridSearchCV

---

## Results
- **Random Forest** achieved the best accuracy (~90%) before tuning.
- Hyperparameter tuning further optimized model performance.
- Key insights: Students, retirees, and single individuals have higher subscription rates. Cellular contact is more effective than telephone.

---

## Files
- `ML-bank.ipynb`: Full analysis and modeling
- `GH1031192.html`: HTML version of the notebook
- `README.md`: Project description

---

## Conclusion
Targeted marketing using machine learning significantly improves efficiency and conversion rates compared to blanket campaigns.

