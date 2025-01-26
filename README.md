# Support Vector Regression (SVR)

This repository contains an implementation of Support Vector Regression (SVR) using Python. The project demonstrates how to use SVR to predict salary data based on position levels.

## Files

- **`support vector regression.ipynb`**: The Jupyter Notebook contains the implementation of SVR, including data preprocessing, model training, and visualization of the results.
- **`Position_Salaries.csv`**: A sample dataset used in the project, containing position levels and corresponding salaries.

## Project Overview

Support Vector Regression is a type of machine learning algorithm that uses the principles of Support Vector Machines (SVM) to perform regression analysis. Unlike traditional regression methods, SVR works well for non-linear relationships by using kernel tricks.

### Dataset Details

The dataset (`Position_Salaries.csv`) includes the following columns:
- **Position**: The job position.
- **Level**: The numeric representation of the position level.
- **Salary**: The corresponding salary for the position level.

### Key Steps in the Notebook

1. **Data Loading and Exploration**:
   - Load the dataset.
   - Perform basic exploratory data analysis.

2. **Data Preprocessing**:
   - Feature scaling to standardize the input data.

3. **Model Training**:
   - Train the SVR model using the RBF (Radial Basis Function) kernel.

4. **Prediction and Visualization**:
   - Predict salary values using the trained model.
   - Visualize the results to compare the SVR predictions with the actual data.

## Dependencies

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn` (scikit-learn)
