---
title: Electricity Price
emoji: 🦀
colorFrom: yellow
colorTo: indigo
sdk: streamlit
sdk_version: 1.34.0
app_file: app.py
pinned: false
---

# <span style="font-width:bold; font-size: 3rem; color:#2656a3;">**Msc. BDS - M7 Second Semester Project Streamlit** 
EXAM ASSIGNMENT - Repository for Streamlit belonging to the repository [bds_m7_second-semester-project](https://github.com/tobiasmj97/bds_m7_second-semester-project).

## Objectives:
This repository contains all Python files for the final Streamlit application belonging to the second-semester project on the Master in Business Data Science at Aalborg University Business School.

The objective is to make a functional frontend application that visually demonstrates the project’s application in real-world scenarios.
This project aims to build a prediction system that forecasts the electricity prices in Denmark (area DK1) based on weather conditions, previous prices, and the Danish calendar.

## Structure:
There are four Python files in this repository representing each page in the Streamlit app:
1. Price Prediction
2. Explore
3. Performance
4. About

### 🌦Price Prediction
The main page showcases the electricity price predictor for DK1. The page includes two visualizations of the forecasted electricity prices for the coming days where the user can change the date range from 1-5 in the sidebar. Along with a matrix of hourly price intervals, the page showcases an interactive time-series plot in the form of a line chart enabling the user to hover over the line to see the exact price at a specific time.  
 
### 🌎Explore
The Explore page enables a more in-depth exploration of the electricity price prediction. The user can change the desired date range from 1-5. The page enables the user to choose between several different visualizations showcasing the actual electricity prices and the prices predicted by the model.The visualizations enable the models' performances to be translated from technical to non-technical audiences:
- An interactive line chart of the predicted electricity prices compared with the actual electricity prices.
- Box Plot of Electricity Prices visualizing the actual and predicted electricity prices.
- Histogram displaying the actual and predicted electricity prices.

### 📊Performance
The Performance page visualizes the models' performance using validation metrics RMSE, MAE, MSE, and R^2 to demonstrate the performance for a technical audience.  

### 📚About
The About page dives into the Learning Objectives the project is demonstrating and the main objective the frontend application aims to fulfill. 

## Frontend Application on 🤗 Hugging Face Spaces:
The final Streamlit app is hosted on [Huggingface](https://huggingface.co/spaces/Camillahannesbo/Electricity_price).
