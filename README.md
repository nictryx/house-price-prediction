# House Prices Prediction using ML 

## About The Project

This project was originally completed as part of a machine learning project based on Kaggle's **Housing Prices Competition**.

The objective is to predict residential property sale prices using the Ames Housing dataset and a combination of numerical and categorical property features.

## Dataset & Challenge

The original challenge is publicly available on Kaggle:

[**Housing Prices Competition**](https://www.kaggle.com/competitions/home-data-for-ml-course/overview)

This repository contains my own machine learning workflow, preprocessing approach, model implementation, and prediction generation.

## Technical Highlights

* Performed missing-value analysis across the dataset
* Processed numerical and categorical features
* Experimented with **One-Hot Encoding**
* Experimented with **Ordinal Encoding**
* Handled unseen categorical values during preprocessing
* Aligned encoded features between training and test datasets
* Split the training data into **80% training / 20% validation**
* Used **Random Forest Regression**
* Configured the model with **100 decision trees**
* Generated final `SalePrice` predictions for unseen test properties

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Random Forest Regressor
* Jupyter Notebook
* Google Colab
* Git

## How to Run

1. Download `train.csv` and `test.csv` from the Kaggle competition.
2. Open `house_price_prediction.ipynb` in **Google Colab** or Jupyter Notebook.
3. Run the notebook.
4. Upload `train.csv` and `test.csv` when prompted.
5. Continue running the remaining cells in order to preprocess the data, train the model, and generate predictions.

