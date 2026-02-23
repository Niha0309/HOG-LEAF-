
# Leaf Disease Classification Using HOG and Gradient Boosting

## Overview

This project implements a machine learning pipeline to classify leaf images as **Healthy** or **Unhealthy** using Histogram of Oriented Gradients (HOG) feature extraction and gradient boosting algorithms.

## Methodology

* Images are resized and converted to grayscale.
* HOG features are extracted to capture texture and edge information.
* Features are scaled using MinMaxScaler.
* Data is split into training and testing sets (80/20, stratified).
* The following models are trained and evaluated:

  * CatBoost
  * XGBoost
  * LightGBM

## Evaluation

Model performance is assessed using:

* Accuracy
* Precision
* Recall
* F1-Score
* Balanced Accuracy
* Confusion Matrix

## Requirements

```
catboost
lightgbm
xgboost
opencv-python
gdown
scikit-learn
```

## Execution

Run the Jupyter Notebook sequentially to:

1. Download the dataset
2. Extract HOG features
3. Train models
4. Evaluate and compare performance

