# Executive Summary

# This project applies predictive modeling and exploratory data analysis (EDA) to support biological research on crab aging. The primary objective is to develop a robust linear regression model that accurately predicts the age of a crab based on various physical characteristics, with the goal of minimizing Mean Absolute Error (MAE) on a designated test dataset. In parallel, the analysis aims to uncover which features most strongly correlate with crab age, providing deeper biological insights through statistical interpretation.

# To achieve this goal, the dataset underwent extensive cleaning and univariate/bivariate analysis. These steps revealed meaningful patterns, feature distributions, and potential outliers. Correlation analysis and scatterplots identified strong linear relationships between age and features such as shell weight, height, and body dimensions. Multicollinearity was assessed using Variance Inflation Factors (VIF), leading to a simplified regression model that retained only the most informative and independent predictors.

# Model performance was evaluated using a 70/30 train-test split across 500 randomized iterations. This resampling strategy yielded an average MAE of 1.459. With a narrow mean distribtuion around the mean, this consistent performance across the iterations confirms the model’s reliability and its ability to generalize well on unseen data.

## Project Deliverables:
## 1. RShiny App – An interactive tool to explore feature relationships with crab age.
## 2. RMarkdown Report – Full documentation of data preparation, EDA, and modeling.
## 3. Age Predictions – Final model predictions submitted for evaluation.
## 4. GitHub Repository – Code, visualizations, and documentation for reproducibility.
## 5. 7-Minute Presentation – A video overview summarizing the project's goals, methods, and findings.
