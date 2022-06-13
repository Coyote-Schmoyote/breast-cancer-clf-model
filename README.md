# Breast Cancer Classification model

Predicting breast cancer using a machine learning model

This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not somebody has breast cancer.

## 1. Problem definition

The problem presented in this notebook is based on an exercise from 「東京大学のデータサイエンティスト育成講座」. In the original exercise, the accuracy score of the breast cancer prediciton model was 95.8%. The goal in this notebook is to improve the accuracy, with random seed set as 0.

## 2. Data

The data contains information of breat cancer patients, and is donated in 1995 by the University of Wisconsin. It has 569 samples with 32 attributes. This data set is built in scikit-learn, and can be imported using from sklearn.datasets import load_breast_cancer. More information about data set: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

## 3. Features

Attribute information:

* ID number
* Diagnosis (M = malignant, B = benign)
* 3-32: Ten real-valued features are computed for each cell nucleus:
  * a) radius (mean of distances from center to points on the perimeter)
  * b) texture (standard deviation of gray-scale values)
  * c) perimeter
  * d) area
  * e) smootness (local variation in radius lengths)
  * f) compactness (perimeter^2 / area - 1.0)
  * g) concavity (severity of concave portions of the contour)
  * h) concave points (number of concave portions of the contour)
  * i) symmetry
  *j) fractal dimension ("coastline approximation" -1)


## 4. Evaluation

The project will be considered successful if we reach accuracy score higher than 95.8% at predicting whether the patient has a malignant or benign tumor.
