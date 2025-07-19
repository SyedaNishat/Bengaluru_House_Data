#  Bengaluru House Price Prediction

A data science project that builds a predictive model for house prices in Bengaluru using various machine learning algorithms and data preprocessing techniques.

##  Problem Statement

The goal is to predict house prices based on features like location, square footage, number of bedrooms/bathrooms, and more. The dataset contains real estate information for properties in Bengaluru.

---

##  Dataset

- Source: [Kaggle - Bengaluru House Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- Columns:
  - `area_type`
  - `availability`
  - `location`
  - `size`
  - `society`
  - `total_sqft`
  - `bath`
  - `balcony`
  - `price`

---

##  Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Git for version control

##  Exploratory Data Analysis (EDA)

- Visualized missing values, outliers, and distributions
- Extracted numerical square footage from textual entries
- Standardized the `size` column into numerical `bhk`
- Removed extreme outliers using logical rules
- Plotted price vs sqft, location-wise price analysis

##  Model Building

- Applied Linear Regression, Lasso, and Random Forest Regressor
- Used GridSearchCV for hyperparameter tuning
- Final model evaluation using R², MAE, RMSE
- Exported model using Pickle

---

##  Results

- R² Score: ~0.9 (Linear Regression)
- Best performance with cleaned data and location grouping
- Model generalizes well for new inputs in the app.
