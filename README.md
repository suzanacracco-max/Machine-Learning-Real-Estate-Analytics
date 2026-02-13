# King County House Price Prediction
## IronKaggle Mini Project | Machine Learning & Real Estate Analytics

### 📌 Project Summary

This project analyzes one year (May 2014 – May 2015) of residential real estate transactions in King County (Seattle area) to identify the key drivers of housing prices and build predictive machine learning models.

The primary objective was to:
 - Predict house sale prices using property and location features
 - Identify the most influential variables affecting price
 - Perform focused analysis on properties priced above $650,000
 - Simulate real-world real estate market analysis using Python and ML

 ### 🎯 Business Objective

In real estate, pricing accuracy directly impacts:

 - Investment decisions
 - Portfolio evaluation
 - Market positioning
 - Risk assessment

This project demonstrates how machine learning can support data-driven pricing strategies in the housing market.

### 📊 Dataset Description

 - 21 property-level features
 - 1-year transaction period
 - King County, WA
 - Target variable: price

Key variables include:

 - Living space (sqft_living)
 - Property grade
 - Geographic location (latitude, longitude, ZIP code)
 - Waterfront status
 - Year built / renovated
 - Neighborhood averages (sqft_living15)

 ### 🔎 Analytical Approach

#### 1 Data Exploration & Cleaning

 - Removed duplicates
 - Handled missing values
 - Explored distributions and outliers
 - Analyzed correlations
 - Investigated geographic patterns

 ### 2 Feature Engineering & Preprocessing

 - Encoded categorical variables
 - Standardized numerical features
 - Addressed multicollinearity
 - Applied outlier handling
 - Prevented data leakage using pipelines

 ### 3 Modeling Strategy

Baseline and advanced models were trained and compared:
  
 - Linear Regression
 - KNN Regressor
 - Random Forest
 - Gradient Boosting

Hyperparameter tuning performed using cross-validation.

### 📈 Model Performance

Models were evaluated using:
 - R² (Explained Variance)
 - MAE (Mean Absolute Error)
 
Tree-based ensemble methods (Random Forest / Gradient Boosting) outperformed linear models due to non-linear interactions in housing data.

Final selected model:

 - strong generalization (minimal train/test gap)
 - High R²
 - Low MAE

### 🏆 Key Insights

The most influential features impacting house prices:

 1. Living area (sqft_living)
 2. Property grade
 3. Geographic location (lat/long)
 4. Waterfront presence
 5. Bathrooms
 6. Neighborhood characteristics

## 💎 High-Value Properties Analysis (>$650K)

Luxury homes are strongly associated with:
 - Prime location
 - Larger living spaces
 - Higher construction grades
 - Waterfront proximity

## 🧠 Technical Highlights

 - End-to-end ML pipeline implementation
 - Proper train/test split strategy
 - Feature importance analysis
 - Cross-validation & hyperparameter tuning
 - Bias-variance tradeoff management
 - Model comparison framework

## 🛠 Tech Stack

 Python, Pandas, NumPy, Matplotlib / Seaborn, Scikit-learn , Jupyter Notebook

## 📌 Key Takeaways

 - Tree-based ensemble models perform best on structured real estate data.
 - Location and property quality are dominant price drivers.
 - Proper preprocessing and regularization significantly improve model stability.
 - Real estate pricing requires handling non-linear relationships and geographic patterns.

## 🚀 Value Demonstrated

This project showcases:

 - Practical machine learning application to real-world financial data
 - Structured problem-solving and analytical thinking
 - Ability to move from raw data to business insights
 - Strong understanding of regression modeling and evaluation