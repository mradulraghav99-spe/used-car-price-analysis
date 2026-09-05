# Used Car Price Analysis

## Project Overview

This project analyzes used car data to understand the factors that influence car selling prices. The analysis includes data cleaning, exploratory data analysis, visualization, correlation analysis, and machine learning using Linear Regression.

## Dataset

The dataset contains information about used cars, including:

- Car name
- Year
- Selling price
- Kilometers driven
- Fuel type
- Seller type
- Transmission
- Mileage
- Engine
- Maximum power
- Torque
- Number of seats

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. Data loading and understanding
2. Data cleaning
3. Handling missing values
4. Feature extraction and creation
5. Exploratory Data Analysis
6. Business question analysis
7. Correlation analysis
8. Data visualization
9. Outlier analysis
10. Linear Regression
11. Model evaluation
12. Final insights and conclusions

## Machine Learning

A Linear Regression model was developed to predict used car selling prices.

### Features Used

- `km_driven`
- `mileage`
- `engine`
- `max_power`
- `car_age`
- `seats`

### Target Variable

- `selling_price`

### Model Results

- **Mean Absolute Error (MAE):** ₹275,717.72
- **R² Score:** 0.6559
- **Explained Variation:** Approximately 65.6%

The model provides a reasonable baseline for predicting used car prices, although there is room for improvement by including additional categorical features such as brand, model, fuel type, transmission, and seller type.

## Key Findings

- Newer cars generally have higher selling prices.
- Cars with higher kilometers driven tend to have lower selling prices.
- Dealer-listed cars have a higher average selling price than individual sellers.
- Maximum power, engine characteristics, mileage, and car age show relationships with selling price.
- The Linear Regression model explains approximately 65.6% of the variation in selling prices.

## Project Structure

```text
Used_Car_Price_Analysis/
│
├── data/
│   ├── Car details v3.csv
│   └── cleaned_car_data.csv
│
├── notebooks/
│   └── used_car_analysis.ipynb
│
└── README.md
