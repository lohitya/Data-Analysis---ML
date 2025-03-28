# Seoul Bike Sharing Analysis

Overview

This repository contains an in-depth analysis of the Seoul Bike Sharing dataset. The project explores factors affecting bike rentals using data analysis and machine learning techniques.

Project Files

SeoulBikeAnalysis.ipynb: Exploratory data analysis (EDA) of the dataset, including data cleaning, visualization, and statistical insights.

SeoulBikeML.ipynb: Machine learning model development to predict bike rental demand based on various factors.

Dataset
  
  The dataset includes daily records of bike rentals in Seoul along with influencing factors such as:
  
  Weather conditions (temperature, humidity, wind speed, etc.)
  
  Date and time-related attributes (season, holiday, working day, etc.)
  
  Other environmental and seasonal indicators

Libraries Used:

    Pandas, NumPy
    
    Matplotlib, Seaborn
    
    Scikit-learn

# Exploratory Data Analysis (EDA) and Business Insights

1. Seasonal Trends

    Bike rentals peak during summer and decline in winter, indicating a strong seasonal impact on demand.

2. Weather Influence

    Higher temperatures correlate with increased bike usage, while high humidity and heavy rainfall negatively impact rentals.
    
    Weekday vs. Weekend Usage
    
    Weekday rentals are higher during morning and evening hours, suggesting commuter usage, whereas weekends see a more balanced distribution.
    
    Holiday & Working Day Impact
    
    Bike usage is significantly lower on holidays compared to regular working days, showing reliance on bike rentals for daily commuting.

# Machine Learning Model - Supervised Learning (Regression Problem Statement)

The goal is to predict the number of bike rentals based on the given independent variables.

Model Training & Evaluation:

    Feature selection and engineering
    

Training regression models 

    Linear Regression
    Decision Trees
    Random Forest

Evaluating model performance using key metrics:

    Root Mean Squared Error (RMSE)
    
    Mean Absolute Error (MAE)
    
    R² Score


Future Improvements
    
    Try advanced ML models such as neural networks
    
