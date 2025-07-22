# Asthma-Prediction
# 🧠 Asthma Prediction using Machine Learning

This project focuses on predicting asthma in individuals using a synthetic dataset of health and lifestyle indicators. It compares multiple classification models, explores data balancing techniques, and demonstrates model evaluation and tuning.

---

- **Features include:**
  - Age, Gender
  - Smoking status
  - Allergies
  - Air pollution level
  - Physical activity level
  - Comorbidities
  - Occupation type
  - Target: `has_asthma` (0 = No, 1 = Yes)

---

## ⚙️ Preprocessing

- One-hot encoding for categorical variables
- SMOTE applied to handle class imbalance
- StandardScaler used for feature scaling
- Train/test split with stratification


## 📌 Conclusion

- Both Logistic Regression and pruned Decision Tree models perform very well on the test data.
- SMOTE successfully handled the class imbalance problem.
- Pruning was essential to improve the Decision Tree’s generalization and avoid overfitting.
- Final models achieved **>98% accuracy and excellent recall**, making them strong candidates for real-world deployment in healthcare analytics.

---
