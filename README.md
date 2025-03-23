# Decision Trees & PCA Analysis

This project contains three experimental scripts using the Iris dataset and the Breast Cancer Wisconsin datasets. It demonstrates decision tree classification and PCA dimensionality reduction, 和 includes an additional script for visualizing the decision tree structure.See Homework2.0Report.pdf for details

## Contents

- **Problem 1:**  
  Use the Iris dataset to construct binary decision trees with different maximum depths, comparing Recall, Precision, 和 F1 Score.

- **Problem 2:**  
  Use the Breast Cancer Wisconsin discrete dataset to build a decision tree with a maximum depth of 2. It calculates the Entropy, Gini, 和 Misclassification Error at the first split, 和 analyzes the information gain along with the selected feature and threshold.

- **Problem 3:**  
  Use the Breast Cancer Wisconsin continuous dataset. Train a decision tree on the original data, then perform PCA for dimensionality reduction (using 1 and 2 principal components) and compare the performance (F1 Score, Precision, Recall, 和 confusion matrix).

## Dependencies

- Python 3.x
- pandas
- scikit-learn

Additional dependencies (only for decision tree visualization):
- graphviz
- pydot

Install dependencies via:

```bash
pip install -r requirements.txt
