# Reducing Flood Risks in Belgrade Area through AI Solutions

This is a collaborative open source project promoted by Omdena Belgrade Chapter.



Project detailed description: https://omdena.com/chapter-challenges/reducing-floods-risks-in-belgrade-area-through-ai-solutions/


## Objectives

The main goal is be the creation of a supervised ML model, based on historical weather and hydrological data for Danube, Sava and other small rivers in Belgrade area, which will bring a prediction of possible floods in the future. 

## Data collection


![All Features](./images/all_features.png)

## EDA - Exploratory Data Analysis

<img src="./images/corr_matrix.png" width="900" height="800">


## Time Series Forecasting Models


*Table 1: Error metrics for each model implemented.*


<img src="./images/results_1.png" width="420" height="280">



*Table 2: Descriptive statistics for the absolute error of each model.*


<img src="./images/results_2.png" width="600" height="280">



<img src="./images/Linear Regression AR.png" >

<img src="./images/XGBoost AR.png" >

<img src="./images/MLP Regression AR.png" >

<img src="./images/GRU AR.png" >

<img src="./images/CONV-1D AR.png" >

<img src="./images/LSTM AR.png" >






## Streamlit Web App Deployed

The team deplyed a web app created with Streamlit Python framework for simple predictions based on the time serires forecasting models developed.

https://mussb00-streamlitdeploymen-task-6-model-deploymentdeploy-vbkt2l.streamlit.app/

![Web App](./images/web_app.png)
