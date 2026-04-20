# Price My Car

## Overview

Price My Car is a Flask-based web application that predicts the price of a used car using a machine learning model. The prediction is based on inputs such as car company, model, manufacturing year, fuel type, and kilometers driven.

The application uses a Linear Regression model trained on cleaned car data to estimate a fair market price.

---

## Features

- Predicts used car prices using machine learning
- Simple and clean web interface
- Supports multiple car brands and models
- Considers year, fuel type, and mileage
- Provides instant price prediction

---

## How It Works

1. User enters car details (company, model, year, fuel type, kilometers driven)
2. Data is sent to the backend Flask server
3. The trained model processes the input
4. The predicted price is displayed on the webpage

---

## Project Structure

Price-My-Car/

│
├── app.py

├── LinearRegressionModel.pkl

├── Cleaned_Car_data.csv

│
├── templates/

│   └── index.html
│

├── static/

│   ├── css/

│   └── js/
│

└── README.md

---

## Future Improvements

- Improve accuracy using advanced ML models (Random Forest, XGBoost)
- Add location-based pricing
- Deploy on cloud platforms
- Add user authentication system
- Add analytics dashboard

---

## Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML
- CSS
- Bootstrap
- Pickle

---

## Disclaimer

This project provides estimated prices only. Actual market prices may vary based on condition, location, and market demand.
