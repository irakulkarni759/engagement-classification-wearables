# engagement-classification-wearables

Detecting cognitive engagement (focus) using physiological and environmental features compatible with consumer wearables. Models include logistic regression, SVM, random forest, and XGBoost, trained on the Kaggle Emotional Monitoring Dataset.


# Engagement Classification Using Wearable-Compatible Biometrics
This project explores whether user engagement states can be predicted using physiological and environmental data measurable via consumer wearables. The goal is to build a lightweight model deployable in real-time applications such as productivity tracking or focus monitoring.

## Dataset
Kaggle Emotional Monitoring Dataset  
➡ Only wearable-compatible features retained (e.g., heart rate, skin conductance, temperature, ambient noise, light).

## Models Implemented
- Logistic Regression (baseline)
- SVM (linear and RBF kernel)
- PCA for visualization
- Random Forest
- XGBoost

## Evaluation Metrics
- Accuracy
- F1 Score
- ROC-AUC
