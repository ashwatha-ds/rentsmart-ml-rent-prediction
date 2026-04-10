RentSmart – Rent estimation & Location Recommendation System

Live Demo

https://rentsmart-ml-rent-prediction-rk2d4wyyj7bvwpymwfvfsx.streamlit.app

Overview

RentSmart is a machine learning-based web application designed to assist users in:

Estimating rental prices based on property features
Identifying suitable locations within a specified budget
The project demonstrates a complete end-to-end data science workflow, including data preprocessing, exploratory data analysis, model development, and deployment.

Key Features

Rent Prediction

The application predicts rental values based on:

Zone and location
Property type
Number of bedrooms
Furnishing status
Parking availability
Lift availability
Built-up area
Location Recommendation

Recommends top locations based on user preferences
Filters properties within a defined budget range
Displays approximate average rent for comparison
Disclaimer

Predictions are approximate and may vary depending on real-world housing market conditions.

Dataset

The dataset used in this project is inspired by real-world housing data and has been processed and modified for educational purposes. It is not intended for redistribution or commercial use.

Technology Stack

Python
Pandas
NumPy
Scikit-learn
Streamlit
Project Structure

rentsmart-ml-rent-prediction-app/
│
├── new_app.py
├── model_final.pkl
├── encoders_final.pkl
├── requirements.txt
├── FINALISED DATASET FOR PROJECT.xlsx
├── rent_prediction_analysis.ipynb
Running the Application Locally

Clone the repository

Install dependencies:

pip install -r requirements.txt
Run the application:

streamlit run app.py
Model Information

Supervised machine learning model trained on housing data
Includes preprocessing and encoding pipelines
Evaluated using regression metrics
Future Enhancements

Improve model performance through tuning and feature engineering
Incorporate additional data sources
Enhance user interface and user experience
Expand recommendation capabilities
