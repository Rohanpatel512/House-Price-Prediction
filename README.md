# House-Price-Prediction

## Description
This project is a machine learning model that predicts house prices based on various features
such as living space, number of bedrooms, and more. The model used in this project is the **Gradient Boosting 
Regressor**, achieving an R^2 score of 0.853.

## Dataset
- The dataset consists of 39,981 house listing with various attributes
- Some key features used for prediction
  - 'Zip Code' - The zip code of the house.
  - 'Beds' - Number of bedrooms.
  - 'Baths' - Number of bathrooms.
  - 'Living Space' - Total area of house interior space.
  - 'City' - City house is located in.
  - 'State' - State house is located in.
  - 'Median Household income' - Median income of house owners.

## Libraries 
- Pandas - For data preocessing and feature engineering.
- NumPy - For data manipulation.
- Seaborn & Matplotlib - For data visualization.
- Scikit-learn - For training and testing model.

## Results
| Model | R^2 (train) | R^2 (test) | RMSE (test) | MAE (test)
|--------|------------|------------|----------------|---------------|
| **Gradient Boosting Regressor** | 0.853 | 0.882 | 194889 | 10895 |


