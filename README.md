# ML Assignment 4: California Housing Regression Analysis

## objective
The objective of this project is to evaluate various regression techniques by predicting median house prices in California. The project covers the full ML pipeline: preprocessing, EDA, model implementation, and hyperparameter tuning.

## Dataset
The **California Housing dataset** (from `sklearn.datasets`), containing 20,640 samples with 8 features such as Median Income, House Age, and Location.

## Instructions to Run
1. Clone this repository.
2. Ensure you have the following libraries installed: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.
3. Open the `assignment_4.ipynb` notebook.
4. Run all cells sequentially to see data preprocessing, model training, and final evaluation.

## Key Findings
- **Best Model:** Random Forest Regressor (Tuned).
- **Preprocessing:** Standardization was essential for SVR and Linear Regression performance.
- **Top Feature:** Median Income (`MedInc`) showed the strongest correlation with house value.
