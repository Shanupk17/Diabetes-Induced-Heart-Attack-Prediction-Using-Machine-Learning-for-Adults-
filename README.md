# 🩺 **Diabetes-Induced Heart Attack Prediction Using Machine Learning**

A machine learning project to predict heart attack risk in diabetic adults using health indicators like glucose, cholesterol, blood pressure, and lifestyle habits. This system supports **early diagnosis** and **preventive healthcare** by providing interpretable predictions and risk classifications.

---

## 🎯 **Objectives**

- 🔍 Predict heart attack risk in diabetic individuals
- 🧠 Apply and compare multiple ML models
- 📊 Classify patients as **Low**, **Moderate**, or **High** risk
- 🔎 Use **SHAP** to interpret and explain model decisions
- 🏥 Improve preventive healthcare through accurate risk prediction

---

## 🛠️ **Technologies & Tools**

- **Python**, *Pandas*, *NumPy*
- **Scikit-learn**, **XGBoost**, **LightGBM**, **CatBoost**
- **SHAP** – for model explainability
- *Matplotlib*, *Seaborn* – data visualization
- **SMOTE** – handle class imbalance

---

## 🧠 **Project Workflow**

1. **Data Preprocessing**
   - Handle missing values (mean/median)
   - Feature scaling using `StandardScaler`
   - Encode categorical variables using Label Encoding

2. **Feature Engineering**
   - Correlation analysis
   - SHAP-based feature importance

3. **Model Training & Evaluation**
   - Models: *Logistic Regression*, *KNN*, *Random Forest*, *XGBoost*, *LightGBM*, *CatBoost*
   - Cross-validation: Stratified K-Fold
   - Tuning: Grid & Random Search
   - Metrics: Accuracy, Precision, **Recall**, F1-score, ROC-AUC

4. **Prediction & Classification**
   - Outputs patient risk level: **Low**, **Moderate**, or **High**

5. **Interpretation using SHAP**
   - Visualize feature impact
   - Enable explainable, trustworthy predictions

---

## 📈 **Key Results**

- **Logistic Regression** delivered the highest *recall*, ensuring fewer missed high-risk cases
- SHAP helped explain predictions by showing the contribution of features like *cholesterol*, *stress*, and *age*
- Risk categorization aids doctors in making fast, informed decisions

---

## 🔍 **Example Use Case**

> A 56-year-old diabetic with high cholesterol and stress inputs their data.  
> The system predicts **High Risk** and explains that *cholesterol* and *stress* contributed most to the prediction.  
> The doctor is alerted and can take immediate preventive action.

---

## 📂 **Project Structure**

