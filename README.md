# Predicting Startup Success with Machine Learning

**AI & Machine Learning for Business (CS6471) – MSc Business Analytics, University of Limerick** | Group project (3 members)

## Business problem
Build a bias-aware tool that helps investors and founders judge whether a startup is likely to succeed. The model uses funding, revenue, valuation, customer base, age and industry.

## Data
- [Global Startup Success Dataset](https://www.kaggle.com/datasets/hamnakaleemds/global-startup-success-dataset) (Kaggle): **5,000 startups** across industries and countries

## Method
- Exploratory data analysis, feature engineering (including industry-normalised financial measures), scaling and one-hot encoding
- Models compared: Logistic Regression, Decision Tree, KNN, Naive Bayes, Random Forest, XGBoost
- Evaluation used an 80/20 train-test split, 10-fold cross-validation, ROC-AUC, and precision/recall for each class

## Key findings
- **Final model: Logistic Regression**, with **96.9% test accuracy, ROC-AUC 0.997** and 10-fold CV accuracy of 97.3%
- XGBoost had slightly higher accuracy (97.1%) but missed more successful startups
- We chose Logistic Regression for its strong recall on successful startups and coefficients that are easy to interpret. Both matter in investment decisions.

## Files
- `AIML_Project_Report.pdf`: full report

## Team
Priya Kumari, Chris Caitan Ruzario, Asif Ahmed

## Skills shown
Machine learning · Classification · Model evaluation · Python · Investment risk assessment
