# California Housing Price Prediction

A machine learning project based on the California Housing dataset example from O'Reilly's "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" book.

## Overview

This project analyzes California housing prices using various machine learning techniques to predict median house values based on metrics such as location, population, and housing characteristics.

## Dataset

The dataset contains information about California housing prices from the 1990 census, including:
- Location (latitude/longitude)
- Housing characteristics (rooms, bedrooms, age)
- Population metrics
- Income levels 
- Ocean proximity
- Median house values (target variable)

## Features

- Data cleaning and preprocessing
- Exploratory data analysis with visualizations
- Feature engineering
- Implementation of multiple ML models:
  - Linear Regression
  - Decision Tree Regression
- Model evaluation using cross-validation

## Requirements

```python
pandas
numpy 
matplotlib
scikit-learn
seaborn
```

## Key Techniques Used

- Stratified sampling
- Missing value imputation
- Feature scaling
- One-hot encoding
- Custom transformers
- Pipeline construction
- Cross-validation

## Project Structure

- `california_housing.ipynb` - Main Jupyter notebook containing analysis
- `housing.csv` - Dataset file

## Getting Started

1. Clone this repository
2. Install required packages: `pip install pandas numpy matplotlib scikit-learn seaborn`
3. Open `california_housing.ipynb` in Jupyter Notebook/Lab
4. Run the cells to see the analysis

## Acknowledgments

Based on the example project from "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" by Aurélien Géron (O'Reilly Media).