## Overview
A machine learning project that uses Gradient Boosting Classifier to predict project risk levels (High / Medium / Low) and explores drivers of cost overruns, schedule deviation, and safety using a BIM/AI-enriched dataset.

This repository contains:
Data preparation, exploratory data analysis (EDA), and feature engineering for 1,000 civil engineering projects
A Gradient Boosting Classifier (scikit-learn) trained to predict project Risk_Level
Visual analytics for cost, schedule, energy/material usage, and safety indicators
Reproducible notebook with evaluation metrics and plots

Tech stack: Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · Jupyter
## Dataset
Kaggle Link: https://www.kaggle.com/datasets/ziya07/bim-ai-integrated-dataset
## Result
- Gradient Boosting achieved strong predictive performance on Risk_Level
- Identified systemic inefficiencies: average cost overrun of ~₹5.1M and delay of ~107 days
- Weak correlation observed between Safety Risk Score and Accident Count
