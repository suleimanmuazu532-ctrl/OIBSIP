# Car Price Prediction with Machine Learning

**Oasis Infobyte Internship · Python Track · Task 3**

## Objective
Build regression models that predict the selling price of a used car from its brand, age, mileage, fuel type, transmission and other attributes.

## Dataset
"Vehicle dataset from CarDekho" from Kaggle (`CAR DETAILS FROM CAR DEKHO.csv`): car name, year, selling price (₹), kilometres driven, fuel, seller type, transmission and owner.
Place the downloaded CSV in this folder before running the notebook.

## Approach
1. Data cleaning: null values, duplicates, inconsistent categorical values
2. Feature engineering: car age from the year column, brand extracted from the car name
3. EDA: price distribution, price vs. fuel type (box plot), price vs. car age (scatter plot), average price by brand
4. One-hot encoding of categorical variables
5. Feature correlation heatmap
6. Train/test split (80/20)
7. Models: Linear Regression, Random Forest Regressor, Gradient Boosting Regressor
8. Evaluation with MAE, RMSE and R²
9. Feature importance chart for the best model

## Results
| Model | MAE (₹) | RMSE (₹) | R² |
|-------|---------|----------|-----|
| Linear Regression | _fill in_ | _fill in_ | _fill in_ |
| Random Forest | _fill in_ | _fill in_ | _fill in_ |
| Gradient Boosting | _fill in_ | _fill in_ | _fill in_ |

**Best model:** _fill in after running the notebook_

**Most important features:** _fill in from the feature importance chart_

## Tech Stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Car_Price_Prediction.ipynb
```

## Screenshots
Add screenshots (price distribution, price vs. age, correlation heatmap, model comparison, feature importance) to a `screenshots/` folder.

## Demo Video
_Paste your LinkedIn post link here._
