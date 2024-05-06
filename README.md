# Electrical Energy Prediction - Time Series Forecasting
==============================

This repository contains a data science project to predict electrical energy characteristics for the next few days based on historical time series data.

## Project Overview
This project utilizes time series analysis techniques to forecast electrical energy consumption or generation. The project focuses on:
    
- Data acquisition and pre-processing of historical electrical energy data.
- Building and evaluating machine learning models for time series forecasting.
- Predicting future electrical energy characteristics.


## Data
The project expects a time series dataset containing electrical energy measurements (e.g., consumption in kWh). The data should be in a format compatible with Pandas (e.g., CSV).

## Project Organization
------------

    ├── LICENSE
    ├── Makefile (TO-BE ADDED) <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. 
    │      
    │    
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src (TO-BE ADDED)               <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization (TO-BE ADDED)  <- Scripts to create exploratory and results oriented visualizations 
    │       └── visualize.py
    │


--------

