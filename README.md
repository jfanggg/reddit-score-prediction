# Reddit Score Prediction

## Overview
Final project for 10-605: Machine Learning with Large Datasets. The goal of this
project was to explore different machine learning methods on a sizeable dataset.
The chosen task was to predict a Reddit comment's score given information that
is present at the time of comment posting as a regression problem. We used the
[Reddit Comment Corpus Dataset](https://files.pushshift.io/reddit/comments/).
For computing, we used Microsoft Azure and Google Cloud Platform.

## Repository
The code is organized into several notebooks. The first three notebooks were 
run in Databricks while the multi-layer perceptron notebook was run in Google
Colab. A report is also included.

- `preprocess.ipynb`: read raw data, extract features, and write to storage
- `data_exploration.ipynb`: find statistics such as average and standard 
  deviation for certain features
- `spark_ml_methods.ipynb`: linear regression and random forests code
- `mlp_method.ipynb`: multi-layer perceptron code
- `report.pdf`: report write-up

The multi-layer perceptron code is included for the sake of completeness, 
although I did not play a significant role in writing it.
