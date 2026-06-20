# California housing price prediction

A simple machine learning project that predicts California housing prices using Linear Regression.

## What it does

- Loads the built-in California Housing dataset from scikit-learn
- Explores the data with pairplots and a correlation heatmap
- Scales features using `StandardScaler`
- Trains a Linear Regression model to predict house price
- Evaluates the model using MSE, MAE, RMSE, and R² score
- Checks residuals to validate model assumptions
- Saves the trained model with `pickle`

## Features used

- MedInc (median income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

## Requirements

```
pandas
numpy
seaborn
matplotlib
scikit-learn
```

Install with:
```
pip install pandas numpy seaborn matplotlib scikit-learn
```

## How to run

1. Open `California_Housing_Prices.ipynb` in Jupyter.
2. Run all cells from top to bottom.

No external dataset file is needed — the data is fetched automatically via `fetch_california_housing()`.

## Output

The model prints its coefficients, intercept, and evaluation metrics (MSE, MAE, RMSE, R²), along with plots of predictions vs. actual values and residuals. The trained model is saved as `regressor.pkl`.
