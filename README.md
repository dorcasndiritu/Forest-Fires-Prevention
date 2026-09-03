# Forest Fires Prevention

# Project Overview
This project analyzes the factors associated with forest fire size and severity.
The analysis focuses on exploring environmental factors, building regression models to predict fire area, and developing a classification model to identify lower and higher risk fires.

# Objectives
- Explore factors associated with forest fire size.
- Build and evaluate regression models for predicting fire area.
- Apply diagnostic techniques to assess model performance.
- Use regularization to address multicollinearity.
- Develop a Logistic Regression model for fire-risk classification.

# Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

# Key Findings
- The fire-area target was highly skewed, with many observations having very small or zero fire areas.
- Log-transforming the target improved regression performance compared with the ordinary regression models.
- Ridge and Lasso regression produced very similar results, with Ridge performing slightly better.
- Logistic Regression achieved approximately 53.4% accuracy for classifying fire-risk levels.
- The analysis identified substantial multicollinearity among several environmental predictors.
