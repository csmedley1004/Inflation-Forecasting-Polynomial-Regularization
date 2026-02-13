Forecasting Inflation: Polynomial Feature Engineering & Regularization

📌 Project Overview

This project investigates a central challenge in econometrics: Can machine learning improve short-term inflation forecasting by capturing non-linear relationships? Using global economic indicators (M2 Money Stock, Oil Prices, and CPI data), I developed a predictive framework that compares traditional Ordinary Least Squares (OLS) against Ridge and Lasso regression models. The core of the research focuses on the impact of Polynomial Feature Engineering—expanding the feature space to capture complex interactions between economic drivers.

🛠️ Tech Stack

Language: Python 3.x

Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn

Methodology: Time-Series Analysis, K-Fold Cross-Validation, Hyperparameter Tuning (Alpha), L1/L2 Regularization.

🔬 Key Research Questions & Findings

The Complexity Paradox: My research tested whether higher-order interactions improve accuracy or simply introduce noise (overfitting).

Regularization is Non-Negotiable: As model complexity increased via polynomial expansion, OLS performance degraded significantly. Lasso (L1) and Ridge (L2) models were utilized to "shrink" coefficients, effectively managing the bias-variance tradeoff.

Feature Selection: Lasso regression was specifically leveraged for its ability to perform automated feature selection, identifying which economic interactions were truly predictive of global inflation trends.

📂 Repository Structure
Inflation_Forecasting.ipynb: Complete Python implementation (Pre-processing → Modeling → Evaluation).

Inflation_Forecasting_with_Polynomial_Regularized_Regression.pdf : Supplementary paper analyzing the results of project. 

📖 Citation & Academic Context
This project was developed as part of my MSc in Data Science at the University of Exeter. It bridges the gap between traditional economic theory and modern computational statistics.
