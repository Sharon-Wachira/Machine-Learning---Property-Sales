# Machine-Learning---Property-Sales 
## Malaysian Real Estate Price Prediction
### Project Overview

This project explores the Malaysian real estate market using machine learning techniques to predict house prices.
The study addresses the challenges of unpredictable price trends, valuation disparities, and limited forecasting tools in the housing industry.
By leveraging data preprocessing, feature engineering, and predictive modeling, this project provides actionable insights for real estate developers, investors, and policymakers.

### Objectives

Develop and compare machine learning models (Random Forest, XGBoost, KNN) for predicting property prices.

Identify and analyze the key factors influencing housing prices in Malaysia.

Provide insights that support better valuation, investment strategies, and policy planning.

### Methodology

#### Data Preparation

Data cleaning (handling missing values, outliers, formatting issues).

Feature engineering (e.g., Income per House Age, Rooms-to-Bedrooms Ratio).

Encoding categorical variables (Regions, Addresses).

Exploratory Data Analysis (EDA)

Distribution analysis (income, house age, rooms, population).

Correlation heatmaps and feature importance.

Outlier detection using IQR and boxplots.

Model Development

Random Forest → Best balance of performance and interpretability.

XGBoost → Strong performance with advanced feature capture.

KNN Regression → Lower performance, eliminated due to overfitting.

#### Evaluation Metrics

R² (goodness of fit).

RMSE (prediction error).

Cross-validation for robustness.

### Results

XGBoost (R² ≈ 89.7%, RMSE ≈ 111,646) → Most stable and accurate model.

Random Forest (R² ≈ 87.9%, RMSE ≈ 121,110) → Strong predictive power, slightly less robust.

KNN → Overfit training data, poor generalization.

### Key Factors Driving Prices:

Average Area Income (strongest positive impact).

Average Area House Age (newer homes valued higher).

Number of Rooms and Population (moderate influence).

#### Business Insights

Developers & Investors → Focus on affluent neighborhoods with newer homes.

Policymakers → Improve infrastructure to drive demand and increase housing values.

Buyers → Understand why modern homes in high-income regions command higher prices.

#### Limitations

Data restricted to Malaysia (not globally generalizable).

Missing real-world factors like proximity to amenities, security, and political stability.

Model biases due to feature availability and assumptions.

### Advantages of This Project

Demonstrates end-to-end ML pipeline: data cleaning → feature engineering → model training → evaluation.

Highlights practical insights for real estate stakeholders.

Showcases strong technical skills in Python (pandas, scikit-learn, XGBoost), machine learning, and data visualization.
