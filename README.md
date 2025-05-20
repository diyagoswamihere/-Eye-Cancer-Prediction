# -Eye-Cancer-Prediction
This project leverages advanced ensemble machine learning techniques to predict patient outcomes in eye cancer diagnosis. It processes a real-world healthcare dataset, handles imbalanced data using SMOTE, and applies top-tier classifiers (XGBoost, LightGBM, CatBoost) for robust prediction accuracy.

📂 Dataset
File: eye_cancer_patients.csv
Attributes:
Patient demographic details
Diagnosis metadata
Clinical observations
Outcome Status (Target variable)
Missing and duplicate entries are preprocessed. Date fields are parsed to derive the year of diagnosis.

⚙️ Features
1. Imbalanced Class Handling: SMOTE (Synthetic Minority Over-sampling Technique)
2. Feature Engineering:
-One-hot encoding for categorical features
-Date-based feature extraction (e.g., diagnosis year)
3. Pipeline Construction: scikit-learn pipelines for preprocessing and model training
4. Modeling Techniques:
-XGBoostClassifier
-LightGBMClassifier
-CatBoostClassifier
5. Evaluation:
-Confusion Matrix
-Classification Report (Precision, Recall, F1-score)
-Accuracy Score

📊 Model Performance
The notebook compares three ensemble models using standardized metrics:
Accuracy
Confusion Matrix
Precision, Recall, F1-Score
Each model is evaluated using a stratified 80-20 train-test split.

🧠 Insights
XGBoost generally performs well with structured healthcare data.
LightGBM offers faster training time with competitive performance.
CatBoost handles categorical data natively and often excels with default parameters.

🚀 Future Work
Hyperparameter tuning for better performance
Cross-validation implementation
Model interpretability using SHAP or LIME
Integration into a web-based clinical decision support system

