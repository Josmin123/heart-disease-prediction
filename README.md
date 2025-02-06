# Heart Disease Prediction using Machine Learning
### 📌 Overview

This project aims to predict the likelihood of heart disease in a patient using Machine Learning (ML) techniques. The model is trained on medical data including age, cholesterol levels, blood pressure, and other heart-related parameters to provide a risk assessment.

### 🚀 Key Highlights:

- Uses Random Forest Classifier for prediction.
- Performs feature engineering, data cleaning, and scaling.
- Provides risk assessment messages instead of just binary classification.
- Implements model confidence-based risk flagging for better medical insights.

### 🛠 Technologies Used
Python 
Scikit-Learn 
Pandas & NumPy 
Matplotlib & Seaborn

### 📌 Project Workflow
Step 1: Data Preprocessing

✅ Handling missing values

✅ Encoding categorical variables

✅ Detecting and treating outliers

✅ Feature scaling using StandardScaler

Step 2: Exploratory Data Analysis (EDA)

✅ Feature correlation analysis

✅ Visualizing distributions of key variables

✅ Understanding feature importance

Step 3: Model Building & Evaluation

✅ Implemented Random Forest Classifier

✅ Evaluated using Precision, Recall, F1-score, and Accuracy

✅ Fine-tuned decision threshold to improve recall

Step 4: Risk Flagging System

🔴 High Risk: P(Heart Disease) > 75% → Immediate medical attention

🟠 Moderate Risk: 50% < P(Heart Disease) < 75% → Doctor consultation needed

🟡 Borderline: 40% < P(Heart Disease) < 50% → Lifestyle improvements recommended

🟢 Low Risk: P(Heart Disease) < 40% → Maintain healthy habits


### 📈 Model Performance
Baseline Model (Logistic Regression)

Metric	Value

Accuracy	85%

Precision	84%

Recall	85%

F1-score	85%

📌 Improvements were made to enhance recall, reducing false negatives.

 ⭐️ If you found this project useful, please give it a star ⭐ on GitHub! 😊
