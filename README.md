# California Housing Regression Notebook

This project focuses on the notebook [California Housing.ipynb](./California%20Housing.ipynb), which demonstrates a machine learning workflow for predicting housing prices using the California Housing dataset.

## Objective

The notebook trains and compares regression models to predict the median house value in California using feature variables such as median income, house age, average rooms, population, and geographic indicators.

## Included Files

- [California Housing.ipynb](./California%20Housing.ipynb) – main notebook for data loading, preprocessing, model training, and evaluation
- [feature_distributions.png](./feature_distributions.png) – feature distribution plots
- [correlation_matrix.png](./correlation_matrix.png) – correlation heatmap of the dataset
- [learning_curve.png](./learning_curve.png) – learning curve analysis for bias-variance diagnosis
- [alpha_tuning.png](./alpha_tuning.png) – Ridge regression parameter tuning visualization
- [Predictions_visualization.png](./Predictions_visualization.png) – predicted vs actual housing prices

## Notebook Workflow

The notebook covers the following steps:

- Loading the California Housing dataset from scikit-learn
- Inspecting dataset structure and feature information
- Checking for missing values and feature distributions
- Splitting data into training and testing sets
- Scaling numerical features with `StandardScaler`
- Training multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Random Forest Regressor
- Evaluating the models using MSE, RMSE, MAE, and R²
- Visualizing results and analyzing model behavior
- Understanding bias-variance tradeoff through learning curves

## Tools and Libraries

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

## How to Run

1. Open the notebook in Jupyter:

```bash
jupyter notebook
```

2. Open [California Housing.ipynb](./California%20Housing.ipynb)
3. Run the cells in order to reproduce the analysis and the generated plots.

## Image Outputs

The images in this folder help interpret the model and data:

- `feature_distributions.png` shows how key features are spread
- `correlation_matrix.png` highlights relationships between variables
- `learning_curve.png` indicates if the model is underfitting or overfitting
- `alpha_tuning.png` shows the effect of Ridge regularization strength
- `Predictions_visualization.png` compares predicted vs actual home values

This README is scoped to the notebook and companion image outputs in this folder.
