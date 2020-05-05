# Project-1-Iris-Flower-Classification

## Introduction:
One of the very famous classification problems in Machine Learning is the IRIS Flower classification problem.

**An example of iris flower and the features of our model**</br>
![](https://miro.medium.com/max/578/0*1lgB-Yqej6VPER00)

**Images of the three classes of iris considered in this model**</br>
![](https://miro.medium.com/max/1216/0*rhP_m_pskOF_MUad)

## Problem Statement:
Given Sepal and Petal lengths and width predict the class of Iris.

## Requirements:
- Jupyter Notebook

## Iris-Dataset:
The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). The individual items are called samples in machine learning, while their properties are called features. The shape of the data array is the number of samples multiplied by the number of features. In this case: our data has 150 samples with 4 features each (sepal length (cm), sepal width (cm), petal length (cm), petal width (cm)). The target array contains the species of each of the flowers that were measured. This array is composed of numbers from 0 to 2.
The meaning of those numbers are directly related to our target names (classes):
- setosa (0)
- versicolor (1)
- virginica(2)

## Importing the Modules:
- SkLearn
- Numpy

## KNeighborsClassifier (KNN):
In pattern recognition, the k-nearest neighbors algorithm (k-NN) is a non-parametric method used for classification and regression. In both cases, the input consists of the k closest training examples in the feature space. The output depends on whether k-NN is used for classification or regression:
- In `k-NN classification`, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
- In `k-NN regression`, the output is the property value for the object. This value is the average of the values of k nearest neighbors.
The **k-nearest neighbors classification algorithm is implemented in the KNeighborsClassifier** class in the sklearn.neighbors module. For our example, we will use Five neighbor(k=5).
![](https://miro.medium.com/max/1300/0*MOPXFV3iVf66AwMV)

## Score:
For this model, the accuracy on the test set is **0.97**, which means the model made the right prediction for **97%** of the irises in the given dataset. We can expect the model to be correct **97%** of the time for predicting the species of new irises.

## Summary:
Albeit simple, the iris flower classification problem (and our implementation) is a perfect example to illustrate how a machine learning problem should be approached and how useful the outcome can be to a potential user.
