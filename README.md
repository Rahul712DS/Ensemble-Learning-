# 🧠 Ensemble Learning Classification

This project explores multiple ensemble learning models to classify user purchase behavior using the **Social_Network_Ads** dataset.

## 📦 Ensemble Models Implemented

- **Bagging**
  - Random Forest (best performing)
  - KNN (base learner)
- **Boosting**
  - Gradient Boosting
  - AdaBoost
- **Stacking**
  - KNN + Decision Tree → Logistic Regression
- **Voting**
  - Logistic Regression + KNN + Random Forest (soft voting)

---

## 📊 Model Comparison (Classification Reports)

| Model                       | Accuracy | F1-score (Macro Avg) | F1-score (Weighted Avg) |
|----------------------------|----------|-----------------------|--------------------------|
| Bagging (Random Forest)    | 0.94     | 0.93                  | 0.94                     |
| Bagging (KNN)              | 0.81     | 0.78                  | 0.81                     |
| Gradient Boosting          | 0.92     | 0.92                  | 0.92                     |
| AdaBoost                   | 0.90     | 0.89                  | 0.90                     |
| Stacking                   | 0.89     | 0.88                  | 0.89                     |
| Voting                     | 0.91     | 0.90                  | 0.91                     |

---

## ✅ Insights

- **Bagging with Random Forest** achieves the highest accuracy and balanced performance.
- **Gradient Boosting** is also strong, especially in class recall.
- **Voting and Stacking** provide decent performance when combining diverse models.
- **Bagging with KNN** underperforms, particularly on the minority class.

---

## 📁 Dataset Used

**Social_Network_Ads.csv**

Features:
- Age
- Estimated Salary

Target:
- Purchased (0 or 1)

