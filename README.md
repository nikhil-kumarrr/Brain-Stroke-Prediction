🧠 Brain Stroke Prediction using Machine Learning

This project predicts the likelihood of a person suffering from a stroke using clinical and demographic data.
The goal is to enable early detection and support doctors in taking preventive measures by leveraging Machine Learning.

✅ Features Included

✅ Complete ML Pipeline (Preprocessing + OneHotEncoding + Scaling)

✅ Class Imbalance Handling using SMOTE and class_weight="balanced"

✅ Model Comparison Dashboard with Logistic Regression, Random Forest, XGBoost, SVM

✅ Performance Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

✅ ROC-AUC Curves plotted for all models

✅ Hyperparameter Tuning using GridSearchCV for best model performance

✅ Clean & Reusable Pipeline (can directly joblib.dump() for deployment)

✅ Future-Ready: Can be integrated with a Streamlit app for real-time predictions

📊 Sample Results (Logistic Regression after SMOTE)
Metric	Score
Accuracy	0.92
Precision	0.78
Recall	0.81
F1 Score	0.79
ROC-AUC	0.94
🧰 Libraries Used

pandas, numpy

matplotlib, seaborn

scikit-learn

xgboost

imblearn

joblib

🧪 Dataset Info

Source: Kaggle – Brain Stroke Dataset

Features: Age, Gender, Hypertension, Heart Disease, Work Type, Residence Type, Avg Glucose Level, BMI, Smoking Status

Target Column: stroke (0 = No Stroke, 1 = Stroke)

📈 Visuals Included

📌 Class Distribution Visualization before and after SMOTE

📌 Correlation Heatmap of numerical features

📌 ROC-AUC Curves for model comparison

📌 Confusion Matrix for best performing model
