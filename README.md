# Wine Quality Classification

## Overview
This project implements a multi-class classification model to predict wine quality based on its physicochemical properties. Various machine learning models, including Logistic Regression, Decision Tree, Random Forest, SVM, and XGBoost, are used for comparison. The project focuses on data preprocessing, feature engineering, hyperparameter tuning, and model evaluation.

## Dataset
- [Wine Quality Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv)
- Contains 11 physicochemical properties of wine (e.g., alcohol content, pH, residual sugar) and a target variable (wine quality score from 3 to 8).

## Features
- Data cleaning and z-score normalization.
- Feature engineering to enhance prediction accuracy.
- Hyperparameter tuning using grid search and k-fold cross-validation.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- XGBoost

## Results
- Best-performing model: **Random Forest** (or replace with your best model).
- Classification Report:  
  | Metric      | Value  |
  |-------------|--------|
  | CV-F1 Score | 0.67   |
  | Test-F1     | 0.65   |

## Visualizations
- Feature importance plot.
- Comparison of model performance using bar charts.
- Cross-validation F1 vs. Test F1 plot.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Instructions to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Wine_Quality_Classification.git
   ```
2. Open `Wine_Classification.ipynb` in Jupyter Notebook or Colab.
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run all cells to reproduce results.

## Challenges and Insights
- **Challenges**: Handling class imbalance and optimizing hyperparameters for multiple models.
- **Insights**: Hyperparameter tuning significantly improved model performance, particularly for Random Forest and XGBoost.
