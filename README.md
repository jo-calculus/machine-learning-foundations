# Machine Learning Foundations

A collection of machine-learning projects covering both **from-scratch algorithm implementation** and practical modeling workflows using scikit-learn.

These notebooks were originally developed across several academic exercises and have been reorganized into a single repository to highlight the underlying machine-learning concepts rather than the original coursework.

## Projects

### K-Means Clustering from Scratch

A manual implementation of K-Means covering:

* Euclidean distance calculation
* Random centroid initialization
* Cluster assignment
* Centroid recomputation
* Iterative convergence
* Elbow-style cluster selection

The project focuses on understanding how centroid-based clustering works internally rather than relying on a library implementation.

➡️ [View notebook](notebooks/kmeans_clustering_from_scratch.ipynb)

---

### Decision Tree Construction with Gini Impurity

A simplified decision-tree classifier built from scratch using:

* Gini impurity
* Weighted split evaluation
* Numerical threshold selection
* Categorical splits
* Recursive tree construction

The project demonstrates the mechanics behind how a decision tree decides where to split observations.

➡️ [View notebook](notebooks/decision_tree_gini_from_scratch.ipynb)

---

### Linear & Logistic Regression from Scratch

Manual implementations of regression models using gradient descent.

Topics include:

* Train-test splitting
* Sum of Squared Errors
* Binary cross-entropy
* Weight initialization
* Feature standardization
* Gradient descent
* Linear regression
* Logistic regression

The notebook includes a wine-quality regression exercise and a Titanic binary-classification example.

➡️ [View notebook](notebooks/linear_logistic_regression_from_scratch.ipynb)

---

### Machine Learning Fundamentals with scikit-learn

A broader survey of common supervised and unsupervised learning methods using scikit-learn.

Topics include:

* K-Nearest Neighbors
* Logistic Regression
* Support Vector Machines
* Linear Regression
* Ridge and Lasso
* Decision Trees
* Gradient Boosting
* K-Means
* Local Outlier Factor
* Classification and regression metrics

➡️ [View notebook](notebooks/machine_learning_fundamentals_sklearn.ipynb)

---

### Similarity-Based Learning

Two applications of similarity and distance:

#### Mushroom Classification

K-Nearest Neighbors classification using different neighborhood sizes and distance metrics.

#### MovieLens User Similarity

A basic collaborative-filtering approach using user-item matrices and cosine distance to identify similar users.

➡️ [View notebook](notebooks/similarity_learning_knn_recommender.ipynb)

---

## Tools

`Python` `pandas` `NumPy` `scikit-learn`
`Matplotlib` `Seaborn` `SciPy`

## What This Repository Demonstrates

Together, these projects cover several fundamental ideas behind machine learning:

* supervised vs. unsupervised learning;
* classification vs. regression;
* similarity-based learning;
* optimization through gradient descent;
* regularization;
* tree-based modeling;
* clustering;
* anomaly detection; and
* model evaluation.

Some notebooks implement algorithms manually, while others use established libraries. The combination provides both an understanding of **how common algorithms work internally** and experience applying them through standard machine-learning tools.

## Data Availability

Several of these projects were originally completed using course-provided datasets that are no longer included in this portfolio repository.

Where the original datasets are unavailable, the notebooks retain their stored outputs so that the workflow, results, and interpretation remain visible without modifying the original analysis.

---

*Academic machine-learning work reorganized for portfolio presentation.*
