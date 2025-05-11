Diabetes-Induced Heart Attack Prediction Using Machine Learning
This project focuses on building a high-accuracy machine learning model to predict heart attack risk in diabetic adults. By analyzing health parameters such as glucose levels, cholesterol, blood pressure, and lifestyle habits, the model aims to support early diagnosis and preventive healthcare.

📌 Project Objectives
Predict heart attack risk in diabetic individuals.

Improve early detection to reduce cardiovascular mortality.

Classify risk into Low, Moderate, or High levels.

Provide model interpretability using SHAP for trust and transparency.

🧠 Technologies & Tools Used
Python, Pandas, NumPy

Scikit-learn, XGBoost, LightGBM, CatBoost

SHAP for model explainability

Matplotlib, Seaborn for data visualization

SMOTE for class imbalance handling

🛠️ Machine Learning Workflow
Data Preprocessing

Missing value imputation

Feature scaling using StandardScaler

Label encoding for categorical variables

Feature Engineering

Correlation analysis

SHAP-based feature selection

Model Training & Evaluation

Models: Logistic Regression, KNN, Random Forest, XGBoost, LightGBM, CatBoost

Stratified K-Fold Cross Validation

Hyperparameter tuning (Grid & Random Search)

Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Risk Classification

Classifies patient as Low, Moderate, or High risk

Result Interpretation

SHAP analysis for transparent predictions and risk factor explanation

🎯 Key Results
Logistic Regression achieved highest recall, critical in reducing false negatives.

SHAP analysis enabled feature-level interpretation, increasing clinical trust.

The system is scalable and suitable for hospital systems, telemedicine, and health screening apps.

🚀 Future Enhancements
Integrate real-time monitoring via wearable devices.

Deploy as a web/mobile app for user access.

Expand to include deep learning models for further accuracy.

