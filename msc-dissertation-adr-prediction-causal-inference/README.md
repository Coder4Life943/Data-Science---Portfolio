# MSc Dissertation – Adverse Drug Reaction Prediction using Machine Learning (2025)

## Research Topic
Causal Inference for Predicting Adverse Drug Reactions Using Electronic Health Records (EHR)

## Overview

This dissertation investigates whether machine learning models can accurately predict the risk of adverse drug reactions (ADRs) in hospitalised patients using clinical, laboratory, and pharmacological data.

Adverse drug reactions are a major cause of preventable patient harm and hospital admissions. Early prediction of ADR risk can support clinical decision-making, reduce patient harm, and improve healthcare resource allocation.

The project focuses on building interpretable machine learning models and analysing how patient characteristics influence ADR risk.

## Objectives

- develop machine learning models to predict ADR risk
- compare model performance using classification metrics
- evaluate model reliability for clinical decision support
- apply explainability techniques to understand predictions
- investigate how patient characteristics influence ADR outcomes
- explore how interpretable AI can support healthcare professionals

## Methods

Two classification models were developed and compared:

- Logistic Regression
- Support Vector Classification (SVC)

Key machine learning steps included:

- data preprocessing and cleaning
- feature selection
- train-test split
- handling class imbalance
- model training
- model evaluation using classification metrics
- explainability using SHAP values

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

Special focus was given to recall (sensitivity), as correctly identifying ADR risk is important for patient safety.

## Key Findings

- both models demonstrated moderate predictive performance
- SVC achieved slightly better recall for identifying ADR risk
- medication burden and laboratory markers were important predictors
- explainability analysis supported clinical relevance of results
- interpretable models can support clinical decision-making

The findings show that machine learning can support early identification of ADR risk and improve patient safety.

## Skills Demonstrated

- machine learning modelling
- classification modelling
- healthcare data analysis
- feature engineering
- model evaluation
- ROC analysis
- confusion matrix interpretation
- explainable AI (SHAP)
- data preprocessing
- working with real-world healthcare datasets
- analytical thinking
- research and academic writing

## Tools Used

Python  
scikit-learn  
pandas  
NumPy  
SHAP  
Jupyter Notebook  

## Repository Contents

| File | Description |
|------|-------------|
| Dissertation_Final.docx | Full MSc dissertation report |
| Full python code.html | complete machine learning implementation |
| Marking descriptors | assessment criteria |

## Impact

This research demonstrates how interpretable machine learning can support safer prescribing decisions and improve early detection of adverse drug reactions.

The project highlights the potential of AI to improve healthcare outcomes through data-driven decision support.
