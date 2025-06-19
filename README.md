Logistic Regression from Scratch in Python

This project demonstrates how I built a Logistic Regression model from scratch, without using any machine learning libraries like Scikit-learn for training. The goal was to understand how the sigmoid function, binary classification, and loss optimization via gradient descent work under the hood.

What this project includes

- Manual implementation of the logistic regression algorithm
- Custom gradient descent optimizer
- Binary Cross-Entropy (Log Loss) calculation
- Visual comparison of predictions from my model and Scikit-learn's model
- Tested on a real-world binary classification dataset: Study Hours vs Pass Outcome

Dataset used

1. study_pass_data.csv
    - Feature: Hours studied
    - Target: Pass (1) or Fail (0)
    - Format: CSV with two columns (Hours, Pass)

Results and Accuracy

For the Study Hours vs Pass Dataset:
    - Scikit-learn Log Loss: 0.3304
    - My Model Log Loss: 0.3338

These results show that my hand-coded model achieves accuracy very close to Scikit-learn’s implementation.

Project files

- study_pass_data.csv – Dataset for classification
- Logistic_Regression_without_sklearn.ipynb – Main Jupyter notebook with all code
- logistic_regression_without_sklearn.py – Main file in Python
- README.md – Project overview

What I learned

- How to implement logistic regression from scratch
- How the sigmoid function transforms output into probabilities
- How to calculate and optimize binary cross-entropy loss
- How to visualize predictions and model behavior
- The value of benchmarking custom models against library implementations