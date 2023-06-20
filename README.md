# Electricity consumption forecasting with ARIMA, UCM & ML models

## Table of contents
* [Abstract](#abstract)
* [Pre-processing](#pre-processing)
* [Modeling](#modeling)
* [Results](#results)

## Abstract

In this project, different models are being tested for forecasting a time series of energy consumption. ARIMA, UCM, and machine learning models are being implemented with the objective of identifying the best solution for predicting the data for the month of December.


## Pre-processing

### Step 1. Download and extract the dataset

Download the dataset from the [official Kaggle Folder](https://www.kaggle.com/datasets/fedesoriano/electric-power-consumption). This project was carried out with only the time series of consumption available: the other variables were hidden, as well as the data for the month of December. Implementing the other attributes present in the dataset is a possible way to improve the results obtained.

### Step 2. Exploratory analysis
In the `Setup&Exploration.Rmd` markdown you can find an exploratory analysis on the dataset, along with some operations useful to prepare the data.


## Modeling

In the `DecemberForecasting.Rmd` markdown, the best models are proposed for the 3 considered classes (ARIMA, UCM, and ML). For each of the considered models, the performance on the validation set is reported, along with the final predictions for the month of December.


## Results

Check out the `Report.pdf` for further details.

## Status

 Project is: ![##c5f015](https://via.placeholder.com/15/c5f015/000000?text=+)  _Done_


# Contributors

* [Gianluca Cavallaro](https://github.com/Gianluca124)
