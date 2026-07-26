# 📉 Explainable Financial Distress Prediction

> An end-to-end machine learning project exploring how financial distress can be predicted among UK retail SMEs using six classification models and Explainable AI.

## Project Overview

Financial distress can be an early warning sign of potential business failure. Identifying vulnerable companies before their financial position deteriorates significantly can help lenders, investors, suppliers and business managers make more informed decisions.

This project develops and evaluates machine learning models for predicting financial distress among UK retail small and medium-sized enterprises.

Six classification algorithms were compared, with Random Forest achieving the strongest overall predictive performance. SHAP was then used to explain which financial indicators influenced the model's predictions.

## Business Problem

Traditional financial analysis often relies on a limited number of accounting ratios and may identify financial difficulties only after substantial deterioration has already occurred.

Machine learning can examine more complex relationships between financial indicators and potentially identify warning signs earlier.

This project explores whether machine learning can support an interpretable early-warning system for financial distress.

## Project Objectives

* Develop a machine learning pipeline for financial distress prediction.
* Compare six classification algorithms.
* evaluate model performance using accuracy, precision, recall, F1-score and ROC-AUC;
* identify the strongest-performing model;
* explain model predictions using SHAP;
* translate the analytical results into practical business insights.

## Dataset

The analysis was conducted using financial statement information for **1,000 UK retail SMEs**.

The original company data was sourced from the Orbis database and covered the period from 2020 to 2024.

The financial variables represented areas such as:

* liquidity;
* profitability;
* leverage and solvency;
* cash flow;
* company size;
* revenue growth.

> **Data availability:** The original Orbis dataset is proprietary and cannot be published in this repository.

## Machine Learning Approach

The project followed these main stages:

1. Data collection and initial exploration
2. Data cleaning and preprocessing
3. Financial variable selection
4. Train-test split
5. Class balancing using SMOTE
6. Hyperparameter tuning using GridSearchCV
7. Model training and comparison
8. Performance evaluation
9. Model interpretation using SHAP
10. Development of business-focused conclusions

## Models Compared

The following classification models were evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine
* Artificial Neural Network
* LightGBM

## Key Result

**Random Forest achieved the strongest overall performance, reaching 90.6% predictive accuracy in the best-performing prediction setting.**

The analysis also identified liquidity and leverage-related measures, particularly the Current Ratio and Debt-to-Assets Ratio, as important predictors of financial distress.

## Explainable AI

Predictive accuracy alone is not sufficient for many financial applications. Decision-makers also need to understand why a company has been classified as financially vulnerable.

SHAP — SHapley Additive exPlanations — was used to:

* identify the most influential financial indicators;
* examine the direction of their effect;
* explain individual company predictions;
* improve the transparency of the Random Forest model.

## Technologies Used

* Python
* pandas
* NumPy
* scikit-learn
* imbalanced-learn
* LightGBM
* SHAP
* Matplotlib
* Jupyter Notebook

## Current Repository Status

This repository is currently being developed into a professional project portfolio.

Planned additions include:

* a cleaned Jupyter Notebook;
* model-performance visualisations;
* SHAP explainability charts;
* project requirements;
* a concise project report.

## About Me

I am a Business Analytics graduate interested in machine learning, data analytics and the use of explainable models to solve practical business problems.

This project was originally developed as part of my MSc Business Analytics degree at the University of Exeter and is being adapted into a concise, recruiter-friendly portfolio project.
