# CognitiveFlow AI

## Cognitive Readiness & Focus Classification System

### Overview

CognitiveFlow AI is a Machine Learning based system that predicts a user's cognitive readiness and focus level using behavioral, productivity, and cognitive factors.

The project analyzes factors such as:

* Sleep Duration
* Screen Time
* Mental Fatigue
* Mental Energy
* Mental Clarity
* Distractions
* Decision Load
* Task Completion
* Effort Level
* Satisfaction

and predicts the user's cognitive state and focus score.



## Problem Statement

Students and professionals often experience productivity loss due to fatigue, distractions, cognitive overload, and poor work-life balance.

This project aims to build an intelligent system capable of estimating cognitive readiness and focus level using machine learning techniques and explainable AI.

## Dataset

* Custom dataset collected using Google Forms
* Approximately 500 survey responses
* Data cleaned and preprocessed before training
* Additional feature engineering performed to improve prediction performance

---

## Machine Learning Pipeline

### 1. Data Collection

* Google Forms survey responses
* Manual validation of collected records

### 2. Data Cleaning

* Missing value handling
* Invalid record removal
* Data transformation

### 3. Exploratory Data Analysis

* Feature distributions
* Correlation analysis
* Target distribution analysis

### 4. Feature Engineering

Created additional cognitive metrics including:

* Cognitive Load Ratio
* Attention Span Duration
* Sustained Attention Efficiency
* Context Switching Cost
* Task Switching Frequency

### 5. Model Training

Models evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest
* Gradient Boosting
* XGBoost
* Stacked Ensemble Model

### 6. Explainable AI

Implemented SHAP (SHapley Additive Explanations) for:

* Feature Importance Analysis
* Model Interpretability
* Decision Transparency

## Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Cross Validation
* R² Score
* Mean Absolute Error (MAE)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* SHAP
* Matplotlib
* Seaborn
* Gradio

## Results

Key outcomes:

* Improved model performance through feature engineering
* High predictive accuracy using ensemble learning
* Explainable predictions through SHAP analysis
* Interactive prediction interface using Gradio

## Future Improvements

* Larger real-world dataset collection
* Real-time cognitive monitoring
* Cloud deployment
* Personalized productivity recommendations

