# 🏠 Real Estate Price Prediction — Regression Analysis

A regression analysis project exploring how property features affect apartment prices using Python and statsmodels.

## 🎯 Objective
Predict apartment prices based on area (m²), number of rooms, kitchens, and bathrooms using Ordinary Least Squares regression.

## 🛠️ Tools Used
- Python, pandas, numpy
- statsmodels (OLS regression)
- matplotlib

## 📊 Key Findings
- Property area showed the strongest effect on price, with each additional m² adding approximately 813.31 PKR to the property value
- Number of bedrooms demonstrated a significant positive relationship, where each additional bedroom increased prices by approximately 89,051 PKR
- The model explained approximately 87.4% of price variance (R² = 0.874), indicating a strong fit for predicting residential property prices

## 📁 Files
- `realstate-price-prediction.ipynb` — Full analysis and model
- `Housing.csv` — Dataset used (housing prices with property features)

## ▶️ How to Run
```bash
pip install pandas numpy statsmodels seaborn matplotlib
jupyter notebook realstate-price-prediction.ipynb
```

## 📈 Model Details

This project employs **Ordinary Least Squares (OLS) regression** to model the relationship between property characteristics and selling prices. The analysis includes:

- **Feature Engineering**: Conversion of categorical variables (main road access, air conditioning, furnishing status) into dummy variables
- **Model Specification**: Linear regression model with 11 predictors including property dimensions, amenities, and location factors
- **Interpretation**: Clear coefficient values showing how each property feature influences the final price

## 🔍 Key Takeaways

✅ **Model Interpretability**: Unlike black-box models, OLS provides clear coefficients showing how each property feature influences price

✅ **Feature Importance**: Identify which characteristics (area, amenities, location) matter most to buyers

✅ **Pricing Strategy**: Use model results to value properties competitively in the market

✅ **Investment Decisions**: Understand the ROI of property improvements based on their price impact
