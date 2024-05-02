# Ridge and Lasso Regression on Synthetic 2-D Data

## Overview
This repository contains a Jupyter Notebook demonstrating Ridge and Lasso regression on synthetic 2-D data. Ridge and Lasso regression are techniques used to tackle overfitting and multicollinearity in linear regression models by introducing a penalty term to the cost function.

## Ridge Regression
Ridge regression adds an L2 regularization term to the linear regression cost function, penalizing large coefficients. It helps in reducing the impact of multicollinearity.

## Lasso Regression
Lasso regression adds an L1 regularization term to the linear regression cost function, which tends to shrink some coefficients all the way to zero, effectively performing feature selection.

## Steps Covered in the Notebook
1. Generate synthetic 2-D data.
2. Split the data into training and testing sets.
3. Perform Ridge and Lasso regression with cross-validation for hyperparameter tuning.
4. Evaluate the models using mean squared error.
5. Plot actual vs predicted values for comparison.

## Requirements
- numpy
- matplotlib
- scikit-learn

## Usage
1. Clone the repository.
2. Open and run the Jupyter Notebook `Ridge_Lasso_Regression.ipynb`.
3. Follow the step-by-step instructions in the notebook to understand Ridge and Lasso regression.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Your Name]

## Acknowledgments
This project was inspired by the need to understand and compare the performance of Ridge and Lasso regression techniques.
