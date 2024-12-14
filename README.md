# Health-Insurance-Cost-Prediction-Web-App

An end-to-end machine learning application designed to predict healthcare insurance costs based on patient data. This app leverages advanced data preprocessing, feature engineering, and machine learning techniques to deliver accurate cost predictions, aiding healthcare providers in cost optimization and patient care management.

Features
Data Preprocessing and Feature Engineering: Handles missing values, outliers, and categorical variables to ensure high-quality input for the model.
Machine Learning Model: Trained with a Random Forest Regressor, achieving 86% accuracy in predicting medical insurance amounts.
RESTful API: Built using Flask to enable seamless integration with other healthcare systems.
Containerized Deployment: Dockerized application for easy deployment and scalability.

Technologies Used
Programming Language: Python
Libraries: NumPy, Scikit-learn, Flask
Deployment: Docker

How It Works
Data Input: Collect patient data (age, BMI, smoking habits, etc.) via the web app or API.
Prediction: Process input data through the trained Random Forest Regressor to predict insurance costs.
Integration: Access predictions via the Flask-based API for integration into healthcare workflows.

Future Enhancements
Expand dataset for broader regional coverage.
Add support for real-time prediction using streaming data.
Explore additional models for enhanced accuracy.
