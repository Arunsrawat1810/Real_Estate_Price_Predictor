# Real Estate Price Predictor

This project aims to predict real estate prices using various regression models. The dataset used is a modified version of the Boston Housing Dataset.

## Dataset Description

The dataset contains the following columns:

- `CRIM`: Per capita crime rate by town.
- `ZN`: Proportion of residential land zoned for lots over 25,000 sq. ft.
- `INDUS`: Proportion of non-retail business acres per town.
- `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- `NOX`: Nitric oxide concentration (parts per 10 million).
- `RM`: Average number of rooms per dwelling.
- `AGE`: Proportion of owner-occupied units built prior to 1940.
- `DIS`: Weighted distances to five Boston employment centers.
- `RAD`: Index of accessibility to radial highways.
- `TAX`: Full-value property tax rate per $10,000.
- `PTRATIO`: Pupil-teacher ratio by town.
- `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
- `LSTAT`: Percentage of lower status of the population.
- `MEDV`: Median value of owner-occupied homes in $1000s.

## Dependencies

The project requires the following Python packages:
- pandas
- numpy
- matplotlib
- scikit-learn

## Installation

Install the required packages using pip:
```bash
pip install pandas numpy matplotlib scikit-learn
