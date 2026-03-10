# Karachi Air Quality Index (AQI) Prediction

This repository contains a data analytics project focused on analyzing and predicting air quality in Karachi using historical weather data. The project utilizes machine learning to forecast the next day's Air Quality Index (AQI), providing a tool for environmental monitoring and public health awareness.

## Project Overview

Air pollution is a critical urban challenge. This project aims to:
* **Analyze** historical patterns of AQI in relation to various weather parameters.
* **Visualize** trends and correlations between temperature, humidity, and pollution levels.
* **Predict** the AQI for the following day using a Random Forest Regression model.

## Features

* **Data Cleaning:** Automated handling of missing values and datetime formatting for time-series consistency.
* **Exploratory Data Analysis (EDA):** Detailed visualizations including time-series plots, distribution charts, and correlation heatmaps.
* **Predictive Modeling:** Implementation of a Random Forest Regressor to capture non-linear relationships in environmental data.
* **Performance Evaluation:** Assessment of model accuracy using Mean Absolute Error (MAE) and R-squared ($R^2$) metrics.

## Tech Stack

* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Environment:** Jupyter Notebook / Google Colab

## Dataset

The analysis is performed on `karachi_daily_aqi_weather.csv`, which includes:
* **Date:** Daily timestamps.
* **AQI:** The target Air Quality Index.
* **Weather Features:** Temperature, Humidity, Wind Speed, and other atmospheric metrics.

## Methodology

### 1. Data Preprocessing
The dataset was cleaned by handling null values and converting temporal data into `datetime` objects for time-series alignment.

### 2. Exploratory Analysis
Identified seasonal peaks in pollution levels and determined key weather drivers of high AQI through correlation matrices.

### 3. Model Training
The data was split into an 80/20 train-test ratio. A Random Forest Regressor with 100 estimators was trained to predict the `Next_Day_AQI`.

### 4. Evaluation
Model performance was visualized with "Actual vs. Predicted" scatter plots and measured using MAE and $R^2$ scores to determine reliability.


Author: Aamina Siyal 

Role: Data/BI Analyst
