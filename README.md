# California Housing Price Prediction

Machine learning model that predicts house prices using Random Forest regression on the 1990 California census dataset.

## Project Overview

| Property | Value |
|----------|-------|
| Goal | Predict California house prices |
| Dataset | 20,640 houses from 1990 California census |
| Algorithm | Random Forest Regressor |
| R² Score | 0.800 |
| MAE | $33,310 |

## Features Used

| Feature | Description |
|---------|-------------|
| `MedInc` | Median income in the neighborhood |
| `HouseAge` | Median house age in block |
| `AveRooms` | Average number of rooms per household |
| `AveBedrms` | Average number of bedrooms per household |
| `Population` | Block population |
| `AveOccup` | Average household occupancy |
| `Latitude` | Block latitude |
| `Longitude` | Block longitude |

## Model Performance

- **R² Score:** 0.800 (explains 80% of price variance)
- **Mean Absolute Error:** $33,310
- **Dataset Split:** 80% training, 20% testing

## Key Insights

- **Median income** is the strongest predictor of house price
- **Location** (coastal proximity) significantly impacts value
- **House age** has minimal correlation with price
- More rooms generally correlates with higher price, but weaker than income

## Project Structure

```
california-housing-price-prediction/
├── california_housing_prediction.ipynb   # Main notebook
└── README.md
```

## Technologies Used

- Python 3
- Scikit-learn (Random Forest Regressor)
- Pandas (data manipulation)
- Matplotlib / Seaborn (visualization)
- Google Colab

## How to Run

1. Open `california_housing_prediction.ipynb` in Jupyter or Google Colab
2. Run all cells in order
3. The model trains automatically and outputs performance metrics and plots

## Future Improvements

- Feature engineering (distance to city centers, school ratings)
- Hyperparameter tuning with `GridSearchCV`
- Deploy as web application using Streamlit

---

**Author:** Abhiram Jillellamudi  
**Contact:** [LinkedIn](https://www.linkedin.com/in/abhiramjillellamudi) | jillellamudi.a@northeastern.edu
