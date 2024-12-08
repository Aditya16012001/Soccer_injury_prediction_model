This project focuses on developing a machine learning-based system to predict major injuries among English Premier League soccer players, with the goal of aiding teams in proactive injury prevention and player management. The project integrates player statistics, match participation data, and historical injury records to identify key risk factors for significant injuries. A comprehensive pipeline was developed, covering data preprocessing, feature engineering, model training, and evaluation.

Key highlights include:

Data Preprocessing and Feature Engineering: The dataset was cleaned and enriched with features like cumulative minutes played, injury history trends, and body mass index (BMI). Advanced techniques like SMOTE (Synthetic Minority Over-sampling Technique) were used to handle class imbalance, ensuring fair model training.

Machine Learning Models: Four algorithms were explored—Support Vector Machine (SVM), Random Forest, XGBoost, and K-Nearest Neighbors (KNN). Each model was evaluated using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.

Model Selection and Performance: The SVM model emerged as the most reliable, balancing sensitivity and specificity while avoiding overfitting, which was an issue with Random Forest and XGBoost. Threshold adjustments and cross-validation ensured the model's robustness and generalizability.

Results and Impact: The project demonstrated that past injury history and match participation are critical predictors of future injuries. The optimized SVM model provides actionable insights, enabling teams to mitigate injury risks effectively.

This project represents a significant step toward leveraging machine learning in sports analytics, providing a scalable and adaptable framework for injury prediction in professional soccer. Future improvements could include integrating real-time data, such as biometric or psychological metrics, to further enhance predictive accuracy.
