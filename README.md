# engagement-classification-wearables
Maintaining attention is critical for cognitive performance and daily functioning, yet individuals frequently experience lapses in focus during tasks like studying, working, or driving. A device that can recognize when a user is becoming disengaged could prompt them to take breaks, reduce distractions, or switch tasks. In this project, I aim to explore whether engagement states can be classified using a limited set of physiological and environmental features that are measurable with current or near-future consumer wearables. The long-term vision would be to integrate such an algorithm into a wearable tool that passively monitors focus and promotes sustained attention throughout the day.

## Dataset
Kaggle Emotional Monitoring Dataset  
- Only wearable-compatible features retained (e.g., heart rate, skin conductance, temperature, activity level, ambient noise).

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

## Results 
The project showed that multimodal biometric data can classify engagement levels with high accuracy. Random Forest and SVM balanced performance and interpretability well, while XGBoost delivered the strongest results overall. This pipeline offers a promising foundation for attention-aware wearable systems. Please see the Wearable Engagement PDF for a full report of interprable motivations, methods, visualizations, and results. 
