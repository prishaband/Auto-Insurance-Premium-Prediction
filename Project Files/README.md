# DSCI 441 Project - Auto Insurance Premium Prediction
Author: Prisha Bandyopadhyay

---

## Project Description
This project aims to predict auto insurance premiums using a synthetic dataset designed to mimic real-world insurance data.  
The goal is to explore how customer attributes such as age, marital status, prior insurance history, and claims frequency influence premium amounts.  
We apply machine learning techniques like Linear Regression, Ridge Regression, and K-Nearest Neighbors (KNN) to develop predictive models.

Through this project, we demonstrate how machine learning can be leveraged for risk assessment and premium optimization in the insurance industry.  
Using a synthetic dataset ensures realistic experimentation without compromising privacy.

---

## Data Source
- **Dataset Title:** Insurance Data - Personal Auto Line of Business
- **Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/samialyasin/insurance-data-personal-auto-line-of-business?resource=download)
- The dataset contains customer demographics, policy details, claims history, and premium amounts.

---

## Methodology
1. **Data Collection and Preprocessing**
   - Handled missing values, encoded categorical variables, and standardized numerical features.
2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions, performed hypothesis testing, and studied correlations with premium amounts.
3. **Addressing Multicollinearity**
   - Used correlation matrices and Principal Component Analysis (PCA) to reduce redundancy among features.
4. **Model Development**
   - Built Linear Regression, Ridge Regression, and K-Nearest Neighbors models.
5. **Model Evaluation**
   - Evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.
6. **Insights**
   - Identified key drivers of premiums such as `Policy_Adjustment`, `Claims_PCA`, and `Credit_PCA`.
7. **Next Steps**
   - Suggest hyperparameter tuning and exploring advanced models like Random Forest and XGBoost.

---

## 📦 Required Packages
Install the following Python packages before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn

