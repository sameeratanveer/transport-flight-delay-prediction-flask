# ✈️ Flight Delay Prediction Web App (ML + Flask + MySQL)
This project is a machine learning-based Flask web application that predicts whether a flight will be delayed and estimates the delay duration (in minutes). The system also includes secure user authentication (login/signup), integrates with a MySQL database for user management, and loads a pre-trained PyTorch model to make real-time predictions.

## Problem Statement
Flight delays are a major inconvenience to passengers and a challenge for airlines. Predicting delays in advance can help in better planning and customer satisfaction. This application aims to:

Predict whether a flight will be delayed or not.

If delayed, predict how many minutes it might be delayed.

## Application Features
🔐 User Authentication

Login / Signup / Logout

Passwords hashed and stored using Werkzeug + SQLAlchemy

📈 Prediction Interface

Users can input flight data to get predictions

Displays prediction results with context

💾 Database Integration

Backend powered by MySQL

User data stored in a users table

## Tech Stack
Backend: Flask (Python)

Machine Learning: PyTorch, Scikit-learn

Database: MySQL (via SQLAlchemy)

Frontend: HTML, CSS (Jinja2 Templates)

Others: NumPy, Werkzeug for password hashing

## Machine Learning Overview
Model Type: Binary classification + regression (delay time)

Framework: PyTorch

Input Features:

Air time

Distance

Model Outputs:

Predicted probability of delay

Estimated delay time (in minutes)

Scaler: StandardScaler used for feature normalization

Model Storage:

Model stored in model.pth

Scaler stored in scaler.pkl

