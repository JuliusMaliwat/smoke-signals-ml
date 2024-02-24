# Smoke Signals: Machine Learning Analysis of Smoking Behavior

## Introduction
This project explores the relationship between smoking habits and various bio-signal indicators using machine learning techniques within the KNIME Analytics Platform. Our goal is to classify individuals as smokers or non-smokers and to identify key health indicators affected by smoking.

## Dataset
We utilize a comprehensive dataset that includes demographic and biomedical data to analyze the impact of smoking on health indicators such as hemoglobin levels, serum creatinine, triglycerides, and HDL cholesterol.

## Workflow in KNIME
The KNIME workflow encompasses data preprocessing, exploratory data analysis, feature selection and transformation, model training (including Random Forest, Gradient Boosting, Multi-Layer Perceptron, and Logistic Regression), and evaluation based on AUC, F1 score, and accuracy metrics.

## Models and Evaluation
- **Random Forest** showed the best performance across the key metrics, making it the primary model for our analysis.
- Evaluation metrics used include Area Under the Curve (AUC), F1 Score, and Accuracy to ensure comprehensive assessment.

## Key Findings
- The study identified critical health indicators linked to smoking.
- Feature importance analysis highlighted hemoglobin levels, GTP, serum creatinine, triglycerides, and HDL cholesterol as significant predictors of smoking status.

## Conclusions
Our machine learning framework successfully classified individuals as smokers or non-smokers and identified key health indicators affected by smoking, contributing valuable insights to the public health domain.

## How to Use
1. Import the KNIME workflow.
2. Load your dataset following the provided schema.
3. Execute the workflow to reproduce the analysis.

## References
Details on the dataset, machine learning models, evaluation metrics, and findings can be found in our comprehensive project report.

---

*This project was conducted using the KNIME Analytics Platform, leveraging machine learning to understand the impact of smoking on various health indicators.*
