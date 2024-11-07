# Algerian Forest Fire Prediction

![Algerian Forest Fire Prediction](https://img.shields.io/badge/Python-3.x-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)

## Overview

This project aims to predict forest fires in Algeria using machine learning models. By analyzing environmental factors and historical data, this tool helps identify potential fire hazards and provides insights for effective fire management.

## Features

- Data preprocessing and feature engineering for forest fire prediction
- Machine learning models to predict fire occurrence based on environmental features
- Visualization of model performance
- User-friendly interface with Streamlit for interactive predictions

## Dataset

The dataset used is the **Algerian Forest Fires dataset**, containing information on weather conditions and fire incidents across different regions in Algeria.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/abhimanyu726/Algerian_forest_fire_pred.git
   cd Algerian_forest_fire_pred
2. **Install Required Packages**
   Install the dependencies using pip:

   ```bash
   Copy code
   pip install -r requirements.txt

3. **Set Up Environment Variables**
If using external APIs or storing sensitive data, create a .env file with required API keys or configurations.

Usage
1. Run the Jupyter Notebook
Open and run the Jupyter notebook forest_fire_prediction.ipynb for data exploration, model training, and evaluation.

   ```bash
   Copy code
   jupyter notebook forest_fire_prediction.ipynb
2. Streamlit Interface
For an interactive web-based prediction tool, use the Streamlit app:

   ```bash
   Copy code
   streamlit run app.py
3. Input Features
Region: The specific region in Algeria
Temperature: Temperature (in °C)
Humidity: Relative humidity (percentage)
Wind Speed: Speed of wind (km/h)
Rainfall: Rainfall (mm)
The model will predict the likelihood of fire occurrence based on these inputs.

##Model
The project employs several machine learning algorithms to achieve optimal predictions. Models used include:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Each model’s performance is evaluated based on metrics like accuracy, precision, and recall.

##Results
Best Model: Random Forest Classifier achieved the highest accuracy with effective predictions.
Feature Importance: Temperature and humidity were identified as the most important features influencing fire incidents.
##Contributing
If you’d like to contribute, please fork the repository and create a pull request with a brief description of the changes.
