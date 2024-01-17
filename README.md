# Cancer-Dataset-Classification
In this repository, we'll be building and training different Machine Learning models using Python (Jupyter Notebook) and scikit-learn to perform binary classification on a Breast Cancer dataset.

Dataset source: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data.

## Objective

The goal is to train predictive (binary classification) models applying different Machine Learning algorithms, while handling, processing and exploring data in a particular way for each of these algorithms.

In each notebook, more than just the hard code, I try to explore some relevant theoretical concepts from the ML algorithms, statistics and data processing as well.

## ML Algorithms used:

1) kNN (k-Nearest Neighbours)

2) Decision Trees

3) Logistic Regression

4) Support Vector Machine

## Dataset Context

(Description from Kaggle)
This dataset contains multiple observations from cell nuclei obtained from patients diagnosed with Bening or Malignant Breast Cancer. Each instance has 30 features, composed of the mean, standard error, and "worst" (mean of the three largest values) of 10 different cell nuclei characteristics:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

The goal is to predict, based on these features, if an observed instance corresponds to Benign (B) or Malignant (M) cancer.
