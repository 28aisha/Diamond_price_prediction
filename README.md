# Diamond_price_prediction

💎 Diamond Price Prediction Using Machine Learning
This project is a full-stack web application that predicts the price of diamonds based on their characteristics using a machine learning model. It is built with a Python backend using Django and a responsive frontend using HTML, CSS, JavaScript, and Bootstrap.

🔍 Features
Predicts diamond prices based on attributes like:

Carat

Cut

Color

Clarity

Depth

Table

Dimensions (x, y, z)

Interactive and user-friendly interface.

Real-time price prediction using a trained regression model.

Clean and modern UI design with Bootstrap.

Error handling and validation for better user experience.

🛠️ Tech Stack
Backend: Python, Django, scikit-learn, pandas, numpy

Frontend: HTML, CSS, JavaScript, Bootstrap

Machine Learning: Linear Regression / Random Forest / XGBoost (customizable)

Model Training: Jupyter Notebook

🚀 How It Works
User Input: The user enters diamond characteristics via the frontend form.

Prediction: Data is sent to the Django backend where the ML model processes it.

Result: The predicted price is returned and displayed on the frontend.

📁 Project Structure
php
Copy
Edit
diamond-price-predictor/
├── predictor/              # Django app with model and views
├── static/                 # Static files (CSS, JS)
├── templates/              # HTML templates
├── ML/                     # Jupyter notebook and trained model
├── db.sqlite3              # Database
├── manage.py
└── requirements.txt
📊 Model Training
The model was trained on the popular Diamonds dataset from Kaggle, cleaned and preprocessed using pandas. Feature engineering and model evaluation were conducted using common metrics like RMSE, MAE, and R² score.

🎯 Objective
To demonstrate how machine learning models can be deployed in real-world web applications using Django and how clean frontend integration can enhance usability.
