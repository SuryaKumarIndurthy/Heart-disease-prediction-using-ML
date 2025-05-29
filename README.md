# ❤️ Heart Disease Prediction using Machine Learning

This project builds a predictive model to detect the likelihood of heart disease based on a range of clinical and demographic features. It involves end-to-end data processing, exploratory analysis, feature engineering, and training of a classification model using Scikit-learn.

## 🗂️ Dataset Overview

- The dataset includes features like:
  - `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure), `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
  - `target`: Binary (1 = presence of heart disease, 0 = absence)

## 🧹 Data Preprocessing

- Handled missing values and categorical encodings
- Standardized numerical features
- Created visualizations to explore feature-target relationships
- Used a correlation heatmap to examine multicollinearity

## 🔍 Exploratory Data Analysis

- Observed class imbalance between heart disease presence and absence
- Found key features with strong correlation: `cp`, `thalach`, `oldpeak`, `ca`, and `slope`
- Visualizations: 
  - Target distribution
  - Feature-wise bar plots
  - Correlation with target

## 🧠 Modeling

- Model: Logistic Regression / Random Forest / Decision Tree (modify based on your final choice)
- Metric: Accuracy, Confusion Matrix
- Used cross-validation to evaluate generalization
- Achieved accuracy around **[insert final score]%** on the validation set

## 📈 Evaluation

- ROC AUC Curve, Confusion Matrix, and accuracy metrics plotted and interpreted
- Feature importance identified (e.g., `cp`, `thal`, `oldpeak` ranked highly)
  
