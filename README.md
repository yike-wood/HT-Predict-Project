# HT-Predict-Project
Predict HT for AIS Patients (tabular data)
# Explanation of files
- stats_clean.ipynb: statistical analysis of tabular data
- univariate_cutoff.ipynb: ROC curve analysis
- ht_classification_baseline.ipynb: machine learning based method, using six algorithms including Logistic Regression, SVM, Decision Tree,XGBoost, LightGBM, and Random Forest. Use Optuna to tune parameters
- ht_classification_fusion.ipynb: machine learning based method, using three fusion algorithms including soft voting, stacking, and proposed knowledge-based method
- model.pkl: fine-tuned models obtained from ht_classification_baseline.ipynb
