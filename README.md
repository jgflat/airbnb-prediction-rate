# Airbnb Price Prediction Project

## Overview

This project analyzes Airbnb listing data from New York City and uses machine learning models to predict nightly Airbnb prices. The project includes data cleaning, exploratory data analysis, visualization, feature engineering, and predictive modeling using Linear Regression and Random Forest Regression.

The goal of the project is to better understand what factors influence Airbnb pricing and compare the performance of different regression models.

---

## Dataset

Dataset used:
- AB_NYC_2019.csv

The dataset contains Airbnb listings in New York City including:
- Price
- Room type
- Borough
- Neighbourhood
- Number of reviews
- Availability
- Host listing counts
- Geographic location

Dataset source:
- Inside Airbnb / Kaggle NYC Airbnb Dataset

---

## Features Used

The machine learning models use the following features:

- neighbourhood_group
- neighbourhood
- room_type
- minimum_nights
- number_of_reviews
- reviews_per_month
- calculated_host_listings_count
- availability_365
- latitude
- longitude

---

## Project Steps

### Data Cleaning
- Filled missing values
- Removed extreme price outliers
- Prepared data for modeling

### Exploratory Data Analysis
Created visualizations including:
- Price distribution
- Prices by borough
- Prices by room type
- Reviews vs price
- Feature importance charts
- Actual vs predicted price plots

### Machine Learning Models
Implemented:
- Linear Regression
- Random Forest Regressor

### Model Evaluation
Evaluated models using:
- RMSE
- MAE
- R² Score

### User Prediction System
Built an interactive prediction system where users can input listing details and receive a predicted Airbnb nightly price.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Author Jeremy Granflaten
