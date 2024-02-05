# Simple Linear Regression Model

This repository contains Python code to perform simple linear regression for predicting salaries based on years of experience. The dataset used in this project (`salary_data.csv`) contains two columns: "YearsExperience" and "Salary".

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/sohamvsonar/linear_regression.git
    ```

2. Install the required dependencies:

    ```bash
    pip install pandas scikit-learn matplotlib
    ```

3. Run the Python script `salary_prediction.py` to train the linear regression model and visualize the results:

    ```bash
    python linear_regression.ipynb
    ```

## Dataset

The dataset used in this project (`salary_data.csv`) contains the following columns:

- `YearsExperience`: Number of years of experience
- `Salary`: Corresponding salary in dollars

## Results

The script generates two plots:

1. Scatter plot showing the actual salary data points (in brown) and the predicted salary values (in green) for the training data.

2. Scatter plot showing the actual salary data points (in brown) and the predicted salary values (in green) for the testing data.

## Dependencies

- Python 3 or above
- pandas
- scikit-learn
- matplotlib

