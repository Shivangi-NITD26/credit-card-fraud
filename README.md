# -ml_project-CREDIT-CARD
 CREDIT CARD FRAUD  DETECTION ML PROJECT
Full dataset can be downloaded from: [Kaggle Link](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

This project focuses on building a machine learning model to detect fraudulent credit card transactions using a real-world dataset. Fraud detection is a critical challenge in the financial industry, where the goal is to identify unusual patterns that may indicate illegal activity.

# -Algorithms Used
Logistic Regression
Decision Tree
Random Forest

# -pAnalysis:
Logistic Regression achieved the highest recall (77%) and the best ROC-AUC score (0.84), indicating strong ability to detect fraud cases. However, it suffers from extremely low precision (1%), meaning a high number of false positives.

Decision Tree provided a better balance between precision and recall, resulting in the highest F1-score (0.19) for the fraud class. It also showed a very high overall accuracy (98%) and a strong ROC-AUC score (0.83).

Random Forest, while commonly effective, performed the worst in this scenario. Its recall (53%) and ROC-AUC (0.64) were significantly lower than the other two models, making it less suitable for this imbalanced fraud detection task.
