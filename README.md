# Linear Regression Model to Predict Employee Salary
## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Results](#results)
5. [Examples](#examples)
6. [Contact Information](#contact-information)

## Project Description
In this modelling project, I built a multilinear regression model to predict employee salary and measure the model performance for different variations of predictors selection for model training. The feature selection-model training process include a base model trained on all the available features in the dataset, features selected using pearson correlation and significance, and finally feature selection using variance thresholding.
The dataset employee attributes and target variable (salary). key features include; Age, Gender, Education level, Job Title, Years of Experience.

#### Preliquisites
To succesfully run the code in prediction notebook, install the following modules
- Pandas
- numpy
- matplotlib
- seaborn
- sklearn

execute the below line of code in your notebook to install the latest version of the above packages.
```python
!pip install pandas numpy matplotlib seaborn sklearn bs4

```

# Usage
---

### Data Preparation
perform the following preprocessing on the dataset to make it suitable for the model and for optimum performance.

- Remove records with missing feature values.
- check for accuracy and consistency.
- Encode character features

### Running the model
split the dataset into training and test. 20% as test set and 80% as training set.

_feature selection:_ The linear regression model is trained on three (3) variation of selected features using various thresholding methods (correlation, variance thresholding etc).

### Model Evaluation
The models predictive performance on test sets is evaluated using the mean squared error, root mean squared error, r2_score metrics. these measure the residual and the relationship between the predictors and the target variable.

### Result
[![model_performance](model_evaluation.png)]


Goto [Model](https://github.com/Gab001-data/Football-Match-Prediction-Model/blob/main/PL_match_prediction.ipynb)

