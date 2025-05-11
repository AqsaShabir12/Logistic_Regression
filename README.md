# Logistic Regression from Scratch 

This repository contains a clean implementation of **Logistic Regression** using only **NumPy**. The model is trained and evaluated on the **Breast Cancer** dataset from `scikit-learn`. The goal is to understand the inner workings of logistic regression, including weight updates using gradient descent and prediction using the sigmoid function.

---

##  File Description

- **logistic_regression.py**  
  A single Python script that:
  - Implements the `LogisticRegression` class from scratch  
  - Loads and splits the Breast Cancer dataset  
  - Trains the model using gradient descent  
  - Predicts and prints test accuracy  

---

## Requirements

Make sure you have the following packages installed:

```bash
pip install numpy scikit-learn
```


## How to Run
Simply execute the script in your terminal:
```bash
python logistic_regression.py
```
This will:
- Load the Breast Cancer dataset
- Train a logistic regression model on 80% of the data
- Evaluate the model on the remaining 20%
- Print the accuracy of the predictions

## Dataset

The [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) is used, containing features computed from digitized images of breast masses.
