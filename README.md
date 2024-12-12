Personality Type Prediction Using Machine Learning

This project aims to predict individuals' Myers-Briggs Type Indicator (MBTI) personality types using machine learning. The dataset consists of 128,061 samples and 9 features, including demographic information (e.g., age, gender, education) and psychological scores (e.g., introversion, sensing, thinking, and judging scores).

Key methods involve data preprocessing (encoding and scaling), hyperparameter tuning with GridSearchCV, and model evaluation using macro F1-score to address class imbalance. Five machine learning algorithms were tested, with Random Forest achieving the best performance (Macro F1-Score: 0.886, Accuracy: 90.6%). Feature importance analysis revealed that psychological scores (e.g., Thinking and Introversion) play the most significant roles in predictions.

The repository contains all relevant scripts, processed data, model results, and visualizations for easy reproduction and further exploration.

NumPy: 1.26.4 

Matplotlib: 3.9.2 

Scikit-learn: 1.5.1 

Pandas: 2.2.2 

XGBoost: 2.1.1

SHAP: 0.45.1 

Plotly: 5.23.0 


