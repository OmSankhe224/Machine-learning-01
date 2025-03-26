# Support Vector Regression (SVR) on California Housing Dataset

This repository contains a complete tutorial on using Support Vector Regression (SVR) to predict median house values based on California Housing data. The tutorial includes implementation of both linear and RBF kernels, evaluation metrics, and hyperparameter tuning using GridSearchCV.

## Contents

- svr_california_housing_tutorial.ipynb : Full Jupyter notebook with markdown explanations and code
- README.md : This file with project overview and instructions
- requirements.txt : List of required Python packages
- LICENSE : Open-source license
- tutorial.docx or tutorial.pdf : Optional formal report for academic submission

## Dataset

The California Housing dataset is available via scikit-learn and includes 8 numerical features describing socioeconomic indicators of housing blocks. The target variable is the median house value for each district.

## Objectives

- Understand the concept of SVR and its use of epsilon-insensitive loss
- Train and evaluate SVR models using both linear and RBF kernels
- Visualize predicted vs actual results
- Perform hyperparameter tuning with GridSearchCV
- Compare performance using R2, MAE, and RMSE

## How to Run

1. Clone the repository:
```
git clone https://github.com/your-username/svr-california-housing.git
cd svr-california-housing
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Open the notebook:
```
jupyter notebook svr_california_housing_tutorial.ipynb
```

## License

This project is licensed under the MIT License.

## Acknowledgements

- Dataset source: California Housing dataset from scikit-learn
- SVR implementation: Scikit-learn's support vector regression module
