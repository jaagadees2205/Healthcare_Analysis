
# Healthcare Data Analysis - Predicting Diabetes Risk

## 📊 Project Overview

This project explores the use of machine learning techniques to predict the risk of diabetes using clinical data from the **PIMA Indians Diabetes Dataset**. The goal is to create accurate, interpretable, and robust models that can aid in early diagnosis and clinical decision-making.

## 🔍 Problem Statement

Diabetes mellitus is a global health concern with serious long-term complications if undiagnosed. Traditional diagnostic methods can be expensive and reactive. This project aims to develop predictive models that leverage common medical measurements for efficient and scalable risk detection.

## 🧠 Models Implemented

We evaluated a range of machine learning models:
- **Logistic Regression** (baseline)
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)** with RBF kernel
- **Shallow Neural Network**
- **Gradient Boosting Machine (GBM)**
- **Voting Ensemble** (combining top models)

## 🧪 Techniques Used

- **Data Preprocessing**: Mean imputation for missing values, normalization
- **Exploratory Data Analysis**: Histograms, heatmaps, correlation matrices
- **Model Evaluation**: Accuracy, AUC, Precision, Recall, F1-Score, Confusion Matrices
- **Model Tuning**: Hyperparameter optimization via cross-validation
- **Class Imbalance Handling**: SMOTE (Synthetic Minority Over-sampling Technique)
- **Interpretability**: Feature importance and Partial Dependence Plots (PDPs)

## 🧬 Key Findings

- **Top Predictive Features**: Glucose, BMI, Age
- **Best Performing Model**: A **Voting Ensemble** of Logistic Regression, Random Forest, and SVM offered the most balanced performance.
- **Interpretability vs Performance**:
  - Logistic Regression and Decision Trees are easier to interpret.
  - Ensemble methods and SVMs offer superior accuracy.

## 📁 Dataset

- **Source**: [PIMA Indians Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**: 8 input variables including Glucose, Insulin, BMI, and Age
- **Target**: Binary outcome (1 = diabetic, 0 = non-diabetic)

## 🛠 Project Structure

```
├── data/               # Raw and preprocessed datasets
├── models/             # Trained model files and saved pipelines
├── notebooks/          # Jupyter/R notebooks for EDA, modeling, evaluation
├── src/                # Source scripts for data processing and modeling
├── results/            # Model metrics, confusion matrices, plots
├── reports/            # Final report, presentation, and visuals
└── README.md
```

## 👨‍💻 Author's 

- **Jagadeeswar Reddy Jillella** - [jagadees2205](https://github.com/jaagadees2205)
- **Vishwas Reddy Dodle** 
- **John Erbynn** 

## 📌 Future Enhancements

- Integrate additional features (e.g., HbA1c, cholesterol)
- Implement explainability methods (e.g., SHAP, LIME)
- Deploy as an API or integrate with healthcare decision systems

## 🔗 Links

- 📂 [Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- 📁 [GitHub Repository](https://github.com/jaagadees2205/Healthcare_Analysis)

