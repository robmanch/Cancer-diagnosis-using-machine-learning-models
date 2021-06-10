# Cancer-diagnosis-using-machine-learning-models

## Introduction
For a human, it can become very difficult to consider many attributes to make a decision, whereas machine learning models are very good in classification for a large set of features. In this project, we classify the instance as malignant or benign based on the attributes.

## Dataset & Features
A machine learning or deep learning model will perform well when it has a good quality dataset. We acquire the data from [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

### Attribute Information:
1. ID number
2. Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

3. radius (mean of distances from the center to points on the perimeter)
5. texture (standard deviation of gray-scale values)
6. perimeter
7. area
8. smoothness (local variation in radius lengths)
9. compactness (perimeter^2 / area - 1.0)
10. concavity (severity of concave portions of the contour)
11. concave points (number of concave portions of the contour)
12. symmetry
13. fractal dimension ("coastline approximation" - 1)

## Feature Engineering
As the range of features vary a lot, we have used some transformations techniques such as Minmaxscaler, and Standard Scaler to enhance the accuracy of the models.

## Modeling Approaches
In this project, we use two machine learning algorithms (Logistic Regression, and Naïve Bayes) to classify the instances into benign and malignant.

### Logistic Regression
Logistic regression is a linear classifier, and its output gives the probability of the prediction being equal to 1 (y=1).

### Gaussian Naive Bayes
Gaussian Naïve Bayes is a generative algorithm, and it is based on the Bayes Theorem. It is very computationally efficient, can be used as a base model to start.

## Results
We got the highest accuracy of 97.87% by using logistic regression and applying the standard scaling technique.

## Refrences
1. The dataset is acquired from [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
