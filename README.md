# Seyi_Portfolio
Analytics Portfolio
 # Ensemble Model for Stroke Detection in Pediatric SCD Patients

## Project Overview
This project develops an ensemble machine learning pipeline to predict stroke risk in pediatric patients diagnosed with Sickle Cell Disease (SCD). 

## Problem Statement
Pediatric patients with Sickle Cell Disease face an elevated risk of stroke, which can result in severe long-term neurological complications or mortality if not detected early. Traditional risk assessment methods may fail to capture complex, non-linear relationships within patient data. There is a need for data-driven predictive models that can assist clinicians in identifying high-risk patients earlier and more reliably.

## Objectives
- Build predictive models to classify stroke risk among pediatric SCD patients
- Apply ensemble learning techniques to improve model performance
- Evaluate models using clinically relevant metrics
- Identify key predictors contributing to stroke risk
- Provide a reproducible and extensible machine learning workflow
- ## Dataset Description
The dataset consists of healthcare records related to pediatric SCD patients, including:
- Demographic attributes
- Clinical and laboratory measurements
- Stroke-related indicators and outcomes

The target variable represents stroke occurrence or risk classification. Data preprocessing steps address missing values, feature scaling, and class imbalance where applicable.

## Methodology
- Data ingestion and exploratory data analysis (EDA)
- Data cleaning, preprocessing, and feature engineering
- Train-test split for model validation
- Implementation of multiple base classifiers
- Construction of ensemble models using voting and/or stacking strategies
- Hyperparameter tuning and cross-validation
- Performance evaluation and comparison across models

## Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

These metrics were selected to account for class imbalance and the clinical importance of minimizing false negatives.

## Key Insights
- Ensemble models outperformed individual base learners in overall predictive performance
- Tree-based models captured non-linear relationships more effectively
- Recall was significantly improved using ensemble approaches, reducing missed high-risk cases
- Feature importance analysis highlighted clinically relevant predictors aligned with domain expectations

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
## How to Run the Project
