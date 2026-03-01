Student Burnout Risk Prediction Using Behavioural Analytics

Project Overview:
This project predicts academic burnout risk using behavioural data from an online learning environment. The model identifies students at risk based on engagement decline, missed submissions, and performance indicators.

Dataset Information:
Dataset Source: Kaggle – Open University Learning Analytics Dataset (OULAD)
This dataset contains:
	Student interaction logs (clickstream data)
	Assessment records
	Final course results
It is suitable for behavioural analytics because engagement behaviour over time can indicate burnout patterns.

Target Variable Definition:
Burnout is not directly labeled.
Risk categories were created using final results:
	Pass / Distinction → Low Risk
	Fail → Medium Risk
	Withdrawn → High Risk

Behavioural Features Engineered:
	Total click activity
	Weekly engagement trend
	Missed submission count
	Average assessment score
	Activity consistency

Models Used:
	Logistic Regression
	Random Forest
	XGBoost

Evaluation Metrics:
	Accuracy
	F1 Score
	ROC-AUC
	Confusion Matrix

Tech Stack:
	Python
	Pandas
	Scikit-learn
	XGBoost
	Plotly
	Google Colab

