# Predicting ESG Sustaniablity Scores from Corporate Financial and Environmental Data

A machine learning pipeline to predict ESG (Environmental, Social, and Governance) scores using supervised regression models. The project includes data preprocessing, model selection with nested cross-validation, hyperparameter tuning, and evaluation through learning curves and residual analysis.

## 📂 Files

- `redicting ESG Sustaniablity Scores from Corporate Financial and Environmental Data
.ipynb`: Full Jupyter notebook containing code, visualizations, and explanations.
- `company_esg_financial_dataset.csv`: The dataset used for training and testing.
- `README.md`: Project overview and usage instructions.

## ⚙️ Features

- Data preprocessing using `Pipeline` and `ColumnTransformer`
- Handling of missing values and feature scaling
- Dimensionality reduction with PCA
- Model selection via nested cross-validation
- Hyperparameter tuning with `RandomizedSearchCV`
- Final evaluation on test set using R², MAE, RMSE
- Learning curve and residual analysis for model diagnostics

## 📊 Final Model

- **Model**: `KNeighborsRegressor` with distance-based weighting  
- **Dimensionality Reduction**: `PCA`
- **Test R²**: 0.9763  
- **Test MAE**: 1.8657  
- **Test RMSE**: 2.5024

## 📚 Requirements

- numpy
- pandas
- scikit-learn
- scipy
- matplotlib
- seaborn
- missingno
- xgboost
- mlxtend

## 🚀 How to Run

1. Clone the repository
2. Open notebook.ipynb in Jupyter or Deepnote
3. Run the cells to reproduce the full pipeline and results

## 🧠 Motivation

The goal of this project was to explore how machine learning can be used to model ESG performance based on company-level financial and environmental data. The work was part of a university machine learning exam and emphasizes model selection best practices, including nested cross-validation.
