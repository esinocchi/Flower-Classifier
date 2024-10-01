# Flower Classifier using Logistic Regression

## Overview

This repository contains a flower classification project that utilizes logistic regression to classify flowers based on the Iris dataset. The dataset consists of three different species of flowers: Setosa, Versicolor, and Virginica, with four key features: sepal length, sepal width, petal length, and petal width.

The project demonstrates a simple yet effective application of logistic regression, a supervised machine learning algorithm, for multi-class classification.

## Dataset

The dataset used in this project is the **Iris dataset**, a well-known dataset in machine learning. It contains 150 samples with the following attributes:

- **Sepal Length** (in cm)
- **Sepal Width** (in cm)
- **Petal Length** (in cm)
- **Petal Width** (in cm)
- **Species**: Setosa (0), Versicolor (1), Virginica (2)

## Project Workflow

1. **Data Preprocessing**:
   - The dataset is loaded and visualized to understand its structure.
   - Data is cleaned, and any necessary transformations (such as encoding labels) are performed.

2. **Model Training**:
   - A logistic regression model is trained on the dataset using the petal and sepal dimensions as features.
   - The model is evaluated using accuracy to determine its performance in classifying flower species.

3. **Prediction**:
   - After training, the model can predict the species of a new flower based on its sepal and petal measurements.

## Code Structure

- **Data Loading and Preprocessing**: The dataset is loaded into a DataFrame, and features are separated from the labels.
- **Model Training**: The logistic regression model is trained on the preprocessed dataset.
- **Model Evaluation**: Accuracy and other metrics can be used to evaluate the performance of the model.
- **Prediction**: A sample prediction is demonstrated for a new flower based on the model.
