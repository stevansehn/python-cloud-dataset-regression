# Regression Models Analysis

This project explores various regression models using the Cloud dataset. It demonstrates techniques like k-fold cross-validation, model evaluation, and feature selection. 

## Key Features

- **K-Fold Cross-Validation:** Performs 10 iterations of 5-fold cross-validation with different random states for Linear Regression, calculating the average R2 score.
- **Lasso Regression:** Uses Lasso regression with alpha=1 to identify attributes with zeroed coefficients.
- **Linear Regression Coefficient Analysis:** Identifies coefficient values for each attribute in a Linear Regression model.
- **Model Comparison:** Compares Linear Regression, Lasso, and Ridge regression models based on RMSE using an 80/20 train-test split.
- **Leave-One-Out Cross-Validation:** Calculates the Mean Absolute Error (MAE) for Linear Regression using Leave-One-Out cross-validation.


## Dataset

The project utilizes the Cloud dataset, which is a collection of data points used for regression analysis.


## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Usage

The code is designed to be run within a Google Colaboratory environment, where it can be executed and modified as required.


## Notes

- The code uses the Google Colaboratory environment and requires the Cloud dataset to be accessible from your Google Drive.
- The specific analysis and model parameters can be adjusted according to the needs of the project.
