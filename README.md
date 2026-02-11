California Housing Price Prediction

Machine learning model that predicts house prices using Random Forest regression.

Project Overview
- Goal: Predict California house prices based on location, demographics, and housing characteristics
- Dataset: 20,640 houses from 1990 California census
- Algorithm: Random Forest Regressor
- Performance: R² = 0.80, MAE = $33,310

Key Features
- Median income in neighborhood
- House age
- Average rooms/bedrooms
- Population density
- Geographic location (latitude/longitude)

Results
The model achieved 80% accuracy (R² score of 0.800) with an average prediction error of $33,310. This demonstrates strong predictive capability for real estate valuation.

Technologies Used
- Python
- Scikit-learn (Random Forest)
- Pandas (Data manipulation)
- Matplotlib/Seaborn (Visualization)
- Google Colab

Model Performance
- R² Score:** 0.800 (explains 80% of price variance)
- Mean Absolute Error:** $33,310
- Dataset Split:** 80% training, 20% testing

Key Insights
- Median income is the strongest predictor of house price
- Location (coastal proximity) significantly impacts value
- House age has minimal correlation with price

Future Improvements
- Feature engineering (distance to city centers, school ratings)
- Hyperparameter tuning with GridSearchCV
- Deploy as web application using Streamlit

---
Author: Abhiram Jillellamudi  
Contact: [www.linkedin.com/in/abhiramjillellamudi] | [jillellamudi.a@northeastern.edu]
---
