# Ames Housing Price Prediction

## About The Project

This project was originally completed as part of a machine learning project based on Kaggle's **Housing Prices Prediction** challenge.

The objective is to predict residential property sale prices using the Ames Housing dataset and a combination of numerical and categorical property features.

## Dataset & Challenge

The original challenge is publicly available on Kaggle:

[**Housing Prices Competition**](https://www.kaggle.com/competitions/home-data-for-ml-course/overview)

This repository contains my own machine learning workflow, preprocessing approach, model implementation, and prediction generation.

## Technical Highlights

* Performed missing-value analysis across the dataset
* Processed both numerical and categorical features
* Experimented with **One-Hot Encoding** and **Ordinal Encoding**
* Aligned encoded features between training and test datasets
* Split training data into **80% training / 20% validation**
* Used **Random Forest Regression** for house-price prediction
* Configured the model with **100 decision trees**
* Handled unseen categorical values during preprocessing
* Generated final `SalePrice` predictions for unseen test properties

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Random Forest Regressor
* Jupyter Notebook / Google Colab
* Git
* GitHub
