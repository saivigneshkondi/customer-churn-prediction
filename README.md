 Customer Churn Prediction using Machine Learning

 
🚀 A Machine Learning project to predict customer churn using Ensemble Learning techniques.

Project Overview


This project predicts whether a customer will discontinue a subscription-based service using machine learning models. The dataset consists of customer details such as age, tenure, balance, credit score, and activity status.

To improve accuracy, we use Ensemble Learning models like:


✅ Logistic Regression (Baseline Model)


✅ Random Forest (Bagging)


✅ XGBoost & Gradient Boosting (Boosting)


✅ Voting Classifier (Aggregating multiple models)


✅ Stacking Classifier (Combining models using meta-learning)



📂 Dataset
Source: Churn_Modelling.csv

Rows: 10,000 customers

Target Variable: Exited (1 = Churned, 0 = Retained)

Key Features:

CreditScore, Age, Tenure, Balance

NumOfProducts, IsActiveMember

Geography, Gender, EstimatedSalary


🛠️ Technologies Used


✅ Python (Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn)



✅ Machine Learning (Logistic Regression, Random Forest, XGBoost, Gradient Boosting)


✅ Ensemble Learning (Voting & Stacking Classifiers)


✅ Data Preprocessing (Label Encoding, Standardization)



![image](https://github.com/user-attachments/assets/4f9270cc-bd24-4b93-9b51-34763d579cf1)


📌 Stacking Classifier performs best with 88.5% accuracy! 🎯

📊 Visualizations


📌 Confusion Matrices for Voting & Stacking Classifiers


📌 Feature Importance Plot (Random Forest)


📌 Bar Chart Comparing Model Performance





