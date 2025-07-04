# Walmart Weekly Sales Prediction

## 🎯 Project Objective
The goal of this project is to predict Walmart's weekly sales using economic and temporal features through linear and regularized regression models (Ridge, Lasso).

## 📄 Project Steps
1. **Data exploration and preprocessing**
   - Removal of rows with critical missing values
   - Extraction of features from the "Date" column (year, month, day, etc.)
   - Outlier filtering on numeric columns
   - Separation of features (X) and target variable (Y)

2. **Baseline model: Linear Regression**
   - Training of a LinearRegression model
   - Coefficient analysis and performance evaluation (R2, RMSE)

3. **Regularization with Ridge and Lasso**
   - Hyperparameter tuning with GridSearchCV
   - Coefficient extraction and comparison
   - Interactive visualization with Plotly

## 📊 Key Results
- The Ridge model provides a good trade-off between accuracy and coefficient stability.
- Lasso did not reduce the number of variables (no zero coefficients), indicating that all features contribute useful information.
- Visualizations help highlight the most influential features on weekly sales.

## 📁 Files Provided
- `projet_Walmart.ipynb` : Main analysis notebook
- `Walmart_Store_sales.csv` : Dataset used