# Breast-Cancer-Classification

Evaluate the performance of different supervised learning techniques on the breast cancer dataset from sklearn.

## Dataset

Breast cancer dataset from sklearn.

## 1. Loading and Preprocessing

Load the dataset:
Use the load_breast_cancer function from the sklearn.datasets module.

Handle missing values:
Check for any missing values in the dataset. Although this dataset typically does not have missing values, it is a good practice to verify and handle them if they exist.
handling missing values Ensures data integrity and prevents errors during model training.

Feature scaling:
Standardize the features by scaling them to have zero mean and unit variance using StandardScaler from sklearn.preprocessing. Many machine learning algorithms (e.g., SVM, k-NN) perform better when features are on a similar scale.

## 2. Classification Algorithm Implementation


1.Logistic Regression:

 Logistic regression is a linear model used for binary classification. It estimates the probability that an instance belongs to a particular class. Effective for binary classification and can provide probabilities of class membership.

2.Decision Tree Classifier:

 A decision tree splits the data into subsets based on the feature values, creating a tree-like model of decisions.
Handles both numerical and categorical data and is easy to interpret.

3.Random Forest Classifier:

 An ensemble of decision trees, random forest aggregates the predictions of multiple trees to improve accuracy and prevent overfitting. 
Provides high accuracy, handles large datasets well, and reduces overfitting.

4.Support Vector Machine (SVM):

 SVM finds the optimal hyperplane that maximizes the margin between two classes. It can use different kernel functions to handle non-linear relationships.
Effective in high-dimensional spaces and suitable for datasets where classes are separable.

5.k-Nearest Neighbors (k-NN):

 k-NN classifies instances based on the majority class of the k-nearest neighbors in the feature space.
Simple and intuitive, works well with small datasets and can capture complex relationships.
