# CSOC-Week-1-Linear-Regression
Implemented Linear Regression models from scratch and compared implementations with and without NumPy on various metrics.

## Features

- Linear Regression 
- Gradient Descent
- Train-test split
- Model evaluation using regression metrics
- Data visualization
- Testing on unseen data

## Project Structure

```
.
├── data/Melbourne_Housing_Price_Dataset                 
├── notebooks/CSOC_Week_1   
└── README.md
```

## Methodology

The workflow consists of:

1. Data Loading
2. Data Preprocessing
3. Model Training using Gradient Descent
4. Performance Evaluation
5. Visualization of Results

## Evaluation Metrics

The model is evaluated using:

- Training Time
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

## Results
Without Vectorized Implementation:
- RMSE value : **541749.59**
- Mean Absolute Error : **350956.30**
- R2 Score : **0.407**
- Training time : **431.527** seconds

With Vectorized Implementation:

- Training time: **1.995** seconds
- RMSE value : **472480.67**
- Mean Absolute Error : **340134.53**
- R2 Score : **0.424**

## Future Improvement

Future improvements can include experimenting with:

- Polynomial Regression
- Regularization (Ridge/Lasso)
- Mini-batch Training
- Early Stopping
- Stochastic Gradient Descent
- Mini-batch Gradient Descent

## Installation

Clone the repository

```bash
git clone https://github.com/arjun1151/CSOC-Week-1-Linear-Regression.git
cd CSOC-Week-1-Linear-Regression
```

