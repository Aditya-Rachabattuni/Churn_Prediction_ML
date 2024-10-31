Dynamic Churn Prediction with Machine Learning
This project is a machine learning application designed to predict customer churn based on factors like customer tenure, monthly expenses, and income. The system helps organizations identify customers likely to leave, enabling them to take proactive retention measures.

Project Overview
Purpose: To help businesses understand customer churn and retain at-risk customers by analyzing customer data.
Tech Stack: Python, Django, SQLite, HTML, CSS, JavaScript.
ML Algorithms: Classification techniques for accurate churn prediction.
Features
Predictive Analysis: Predicts the likelihood of customer churn based on various attributes.
Web Interface: A clean, user-friendly Django-based interface for data input and result visualization.
Data Storage: Uses SQLite for efficient storage and retrieval of customer data and predictions.
Model Accuracy: Achieved high accuracy in predicting churn, aiding in targeted retention strategies.
Installation
Clone the Repository

git clone https://github.com/Aditya-Rachabattuni/Churn_Prediction_ML.git
cd Churn_Prediction_ML
Install Dependencies Ensure Python is installed, then run:

pip install -r requirements.txt
Set Up Database Run migrations to set up the SQLite database:

python manage.py migrate
Run the Application Start the Django server:

python manage.py runserver
Open a browser and go to http://127.0.0.1:8000 to access the app.
