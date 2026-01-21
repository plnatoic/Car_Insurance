# Car Insurance Claim Prediction Analysis

**Master Thesis Project: Business Data Analytics**

## 📊 Overview

This project analyzes car insurance claim data to identify key factors that influence claim rates and build predictive models for risk assessment.

## 🎯 Objectives

1. Identify demographic and behavioral factors affecting insurance claims
2. Build statistical models to test hypotheses about claim predictors
3. Develop machine learning models for claim prediction
4. Provide actionable business insights for insurance pricing

## 📁 Project Structure

### Main Notebook: `Mai_Thanh_Pham_Car_insurance.ipynb`

The analysis is organized into 10 sections:

1. **Setup & Data Loading** - Import libraries and load dataset
2. **Data Cleaning** - Handle missing values and outliers
3. **Exploratory Data Analysis** - Descriptive statistics and distributions
4. **Statistical Testing** - Hypothesis testing (Chi-square, Mann-Whitney U)
5. **Data Preprocessing** - Prepare data for machine learning
6. **Machine Learning Models** - Train and evaluate predictive models
7. **Hypothesis Testing Summary** - Summarize statistical findings
8. **Key Visualizations** - Forest plots, ROC curves, feature importance
9. **Business Insights** - Risk segmentation and recommendations
10. **Executive Summary** - Key findings and business impact

## 🔬 Methodology

### Statistical Analysis
- **Chi-Square Tests** - Test relationships between categorical variables and claims
- **Mann-Whitney U Tests** - Compare numerical variables between claim groups
- **Logistic Regression** - Model claim probability with multiple predictors
- **VIF Analysis** - Check for multicollinearity

### Machine Learning Models
- Logistic Regression
- Random Forest
- XGBoost

### Evaluation Metrics
- ROC-AUC Score
- Precision-Recall AUC
- F1 Score
- Cross-validation

## 📈 Key Findings

### High-Risk Factors
- **Age 16-25**: Highest claim rate (71.83%)
- **Low Credit Score**: Strong negative correlation with claims
- **High Annual Mileage**: 47% claim rate for >14,000 miles
- **Driving Violations**: Significant impact on claim probability

### Low-Risk Factors
- **20-29 Years Experience**: Lowest claim rate (29.8%)
- **Married with Children**: 3% lower claim rate
- **High Credit Score**: Strong predictor of lower risk

## 💼 Business Recommendations

### Priority Actions
1. **Dynamic Pricing**: 35% premium increase for age 16-25 segment
2. **Credit Score Integration**: Add 25% weight in underwriting model
3. **Safe Driver Rewards**: Target 20-29 years experience segment
4. **Family Packages**: Attract married customers with children

### Expected Impact
- Reduce loss ratio by 18-22%
- Improve profitability by $2.5M annually
- Increase retention by 12%

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - pandas, numpy - Data manipulation
  - matplotlib, seaborn - Visualization
  - scipy, statsmodels - Statistical testing
  - scikit-learn - Machine learning
  - xgboost - Gradient boosting
  - imbalanced-learn - SMOTE for class imbalance

## 📊 Dataset

- **Source**: Kaggle - Car Insurance Data
- **Size**: 10,000 records
- **Features**: 19 variables (demographic, behavioral, vehicle)
- **Target**: Binary claim outcome (0/1)

## 🚀 How to Use

1. Open the notebook in Google Colab or Jupyter
2. Run cells sequentially from top to bottom
3. All required libraries will be installed automatically
4. Dataset will be downloaded from Kaggle

## 📝 Outputs

The analysis generates 23 CSV files and 5 visualization files:

### Data Files
- Dataset info and descriptive statistics
- Statistical test results (Chi-square, Mann-Whitney)
- Logistic regression coefficients
- ML model comparison
- Business recommendations and ROI projections

### Visualizations
- Forest plot (Odds Ratios)
- Interaction plot (Age × Experience)
- ROC curves comparison
- Feature importance chart
- Credit score vs claim rate

## 👤 Author

**Mai Thanh Pham**
- Master's Thesis in Business Data Analytics
- December 2024

## 📄 License

This project is for academic purposes.

---

**Note**: This notebook has been structured with clear sections and markdown headers for easy navigation and understanding.
