# Real Estate Price Prediction using Linear Regression

## Overview

This project aims to build a machine learning model to predict real estate prices based on various features such as square footage, number of bedrooms and bathrooms, location, and other property characteristics. 

We will use a real-world dataset of US Real Estate Listings from 2021. To reduce the load of the dataset, **three states** can be selected at the beginning of the analysis.

**Dataset Source**: [Kaggle Real Estate Listings](https://www.kaggle.com/discussions/general/327648)

### Features Included
- Square Footage
- Number of Bedrooms and Bathrooms
- Location (zip code, city, state, street)
- Lot in Acres

## Exploratory Data Analysis

- **Visualization**: Explore relationships between features using Matplotlib.
- **Correlation Analysis**: Investigate correlations between features using heatmaps.
- **Statistical Analysis**: Perform statistical analysis to understand feature importance.

## Modeling with Linear Regression

- The model will be implemented using **scikit-learn**.
- It will be trained on the dataset and evaluated for performance.
- Variations will be explored, including:
  - Lasso Regression
  - Polynomial Regression

## Model Evaluation

The performance of the model will be evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²)** to check how well the model understands the variance.

## Data Visualization

- Compare predicted prices with actual prices to assess the model's performance visually.

## Predictions

- Utilize the trained model to predict housing prices based on the eight specified features.

## Usage

1. Clone this repository.
2. Install the required libraries.
3. Run the main script to execute the analysis and modeling.

## Conclusion

This project demonstrates the application of linear regression for predicting real estate prices, providing valuable insights into the factors that influence housing prices.
