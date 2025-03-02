# Data_Wizards
# Air Performance Dashboard

## Overview
The **Air Performance Dashboard** is an interactive tool designed for the airline industry to monitor and optimize operational efficiency. It provides insights into key factors affecting profitability, including aircraft utilization, maintenance downtime, fuel efficiency, revenue, and operating costs. The dashboard leverages **machine learning models and data visualization techniques** to support decision-making and enhance airline performance.

## Features ✨

### Data Cleaning & Preprocessing 🔧
- Identified and handled missing values and duplicates to ensure data integrity.
- Converted time-based columns into datetime format for accurate analysis.
- Engineered new features from flight schedules and operational data.
- Standardized numerical data for improved model performance.
- Exported the cleaned dataset for further analysis.

### Machine Learning Model 🤖
- **Model Used:** Random Forest Regressor for predicting airline profitability.
- **Key Metrics Evaluated:** RMSE, MAE, R² score for performance assessment.
- **Feature Importance Analysis:** Identified critical factors influencing profit.

### Power BI Dashboard 📊
- **KPIs Tracked:** Flight profitability, fuel efficiency, maintenance downtime, load factor, etc.
- **Visualizations:**
  - Profit trends over time
  - Aircraft utilization vs. profit
  - Cost breakdown analysis
  - Correlation heatmap of key variables
  - Revenue vs. operating costs comparison
- **Interactive Elements:** Filters for aircraft type, season, flight route, and airline operation mode.

## Tools & Technologies Used 🛠️
- **Python (Jupyter Notebook)**: Data Cleaning, EDA, and Machine Learning.
- **Pandas, NumPy, Matplotlib, Seaborn**: Data manipulation and visualization.
- **Scikit-Learn**: Model training and evaluation.
- **Power BI**: Interactive dashboards and reporting.

## Insights 💡
- Identified key operational inefficiencies affecting profitability.
- Analyzed seasonal trends to improve pricing and scheduling.
- Highlighted maintenance downtime impact on revenue.
- Provided actionable insights to optimize fuel efficiency and aircraft utilization.

## How to Use 🚀
1. **Machine Learning Model**
   - Run `Ml.ipynb` in Jupyter Notebook to preprocess data and train the model.
   - Evaluate predictions and analyze feature importance.

2. **Power BI Dashboard**
   - Open `Data Wizard.pbix` in Power BI.
   - Explore different KPIs and filter data as needed.
   - Use insights to make data-driven operational decisions.

## Acknowledgments 🙌
- **[Contributor 1]**: Developed the ML model and conducted data analysis.
- **[Contributor 2]**: Built and designed the Power BI dashboard.
- **[Contributor 3]**: Assisted in data preprocessing, feature engineering, and report compilation.

## Future Improvements 🚀
- Integration of real-time data for live monitoring.
- Advanced predictive modeling for flight scheduling optimization.
- Enhanced explainability with SHAP values for better decision-making.

---
This project aims to empower airline operators with **data-driven insights** to maximize profitability and operational efficiency. ✈️📈

