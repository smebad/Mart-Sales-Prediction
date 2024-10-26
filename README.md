# 📈 Mart Sales Prediction

Predict sales in retail stores using machine learning to gain insights and enhance decision-making! This project uses data preprocessing, feature engineering, and an XGBoost model to predict item outlet sales. Dive into exploratory data analysis, data visualization, and model evaluation to understand how different features affect sales.

---

## 📝 Project Overview

This project analyzes the [BigMart Sales Data](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data) and aims to predict the `Item_Outlet_Sales` for various retail stores. The dataset includes item-specific, outlet-specific, and store-level features.

The project workflow includes:
- **Data Preprocessing**: Handling missing values, encoding categorical variables
- **Exploratory Data Analysis (EDA)**: Analyzing distributions, correlations, and trends
- **Model Training**: Using XGBoost Regressor for prediction
- **Evaluation**: Assessing model performance with R² and RMSE metrics

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`

Install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
## 📊 Exploratory Data Analysis (EDA)
Visualizations used in this project:

* Distribution Plots for Item_Weight, Item_Visibility, and Item_MRP
* Count Plot for Outlet_Establishment_Year to see the distribution of outlet ages
* Correlation Heatmap to observe relationships between numerical features

## 🧠 Model Training
The model used:

* XGBoost Regressor: Selected for its performance and robustness with structured data.

Evaluation Metrics
* R² Score: Measures the proportion of variance in sales explained by the model.
* RMSE (Root Mean Squared Error): Indicates the standard deviation of the prediction errors.

## 🔍 Observations & Insights
* Sales Trends: Higher visibility often correlates with lower sales, while higher MRP generally leads to increased sales.
* Outlet Characteristics: Outlet establishment year and size impact the sales but vary across different locations.

## 🛠️ Future Improvements
* Feature Engineering: Add interaction terms and polynomial features for potential performance gains.
* Hyperparameter Tuning: Optimize model parameters using grid search or random search.
* Additional Models: Experiment with different algorithms like RandomForest or Ridge.
