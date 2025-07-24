# 🌸 iris-knn-classifier
A simple machine learning project that uses the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers based on their features. Built using scikit-learn, this project demonstrates the basics of data loading, model training, prediction, and evaluation.

## 📌 Features
Uses scikit-learn's built-in Iris dataset

Implements KNN (k=3) classification

Splits dataset into training and testing sets

Evaluates accuracy

Makes predictions on sample data

Saves and loads model using joblib

## 📊 Example Output

Feature Names: ['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']
Target Names: ['setosa' 'versicolor' 'virginica']

Training Shape: (105, 4)
Test Shape: (45, 4)
Accuracy: 0.955

Sample Predictions:
['virginica', 'versicolor']

## 💾 Save/Load Model
The trained model can be saved to disk using:

from joblib import dump
dump(knn, 'mlbrain.joblib')
And later loaded for inference:

from joblib import load
model = load('mlbrain.joblib')
model.predict(sample)

## 📚 Dependencies
scikit-learn
numpy
joblib

Install them with:

'''pip install scikit-learn numpy joblib'''
