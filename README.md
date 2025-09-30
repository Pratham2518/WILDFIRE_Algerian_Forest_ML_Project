Forest Fire Prediction Web Application
Overview

The Forest Fire Prediction Web Application is a Flask-based web app designed to predict forest fire-related metrics using a pre-trained Ridge Regression model. The application provides a user-friendly interface for users to input environmental parameters and receive predictions, with proper data preprocessing handled automatically using a StandardScaler.

Features

Web Interface: Clean and intuitive HTML/CSS interface served via index.html and home.html.

Machine Learning Model: Integrates a pre-trained Ridge Regression model for predicting forest fire metrics.

Data Preprocessing: Scales input features with a pre-trained StandardScaler for accurate predictions.

Prediction Endpoint: /predictdata handles prediction requests and returns results dynamically.

STRUCTURE
forest-fire-ml-project/
│
├── dataset/
│   └── algerian_forest.csv       # Dataset used for training (example)
├── models/
│   ├── ridge.pkl                 # Pre-trained Ridge Regression model
│   └── scaler.pkl                # Pre-trained StandardScaler
├── notebooks/
│   └── Machine Learning Project 1.2.ipynb  # Model development notebook
├── templates/
│   ├── home.html                 # Homepage template
│   └── index.html                # Index template
├── app.py                        # Main Flask application file
└── requirements.txt              # Python dependencies

