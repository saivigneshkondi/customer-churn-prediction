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

📌 Model Performance
Model             	Accuracy  Precision	  Recall	 F1-Score
Logistic Regression	80.5%	    58.6%	      14.3%	   22.9%
Random Forest	      86.1%	    72.4%	      38.5%	   50.2%
XGBoost	            87.2%	    75.1%	      41.8%	   53.9%
Gradient Boosting	  86.7%	    74.2%	      39.9%	   51.8%
Voting Classifier	  88.0%	    76.5%	      44.2%	   56.1%
Stacking Classifier	88.5%	    77.3%	      46.0%	   58.2%

📌 Stacking Classifier performs best with 88.5% accuracy! 🎯

📊 Visualizations
📌 Confusion Matrices for Voting & Stacking Classifiers
📌 Feature Importance Plot (Random Forest)
📌 Bar Chart Comparing Model Performance





