# Bahrain-Customer-Churn-Prediction
Bahrain Telco B2B Customer Churn Prediction &amp; Decision Support System
An end-to-end Machine Learning and Business Intelligence solution designed to predict customer churn risk, uncover core drivers of attrition, and drive proactive retention strategies for telecommunications enterprises in Bahrain.

Key Features:
Robust ML Ensemble Model: Built using a carefully tuned Balanced Ensemble pipeline (Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting) optimized with class_weight='balanced' to authentically handle class imbalance without relying on synthetic data generation (SMOTE).

Interactive B2B Streamlit Dashboard: A bilingual-ready web portal featuring two core analytical modules:

Macro Portfolio Insights: Executive-level overview tracking general churn health percentages, customer volume at risk, and automated strategic recommendations.

Individual Customer Prediction (Micro): Real-time interactive assessment tool allowing decision-makers to input customer parameters (tenure, charges, contract type, and payment methods) to compute instant churn probabilities and targeted intervention strategies.

Production-Ready Artifacts: Fully serialized model assets (churn_model.pkl and model_columns.pkl) coupled with automated exploratory data analysis and feature importance visualizations.

Tech Stack:
Languages & Core Libraries: Python, Scikit-Learn, Pandas, NumPy, Joblib

Visualization: Seaborn, Matplotlib

Web Deployment Framework: Streamlit
