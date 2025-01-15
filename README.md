## Overview
The goal of this project is to build a Dash web application that predicts the ride price using a trained Gradient Boosting model. The model is trained on a dataset containing features like distance, demand, time of day, and weather conditions. The app allows users to input these factors and get a predicted price for the ride.

## Features
Input fields: Users can input the following:
Distance (in kilometers)
Demand Index (a rating from 1 to 10)
Time of Day (Morning, Afternoon, Evening, Night)
Weather (Clear, Rainy, Snowy)
Prediction: Once all inputs are provided, the app predicts the ride price using the trained Gradient Boosting model.

### Model Evaluation
The best model was selected based on the Mean Absolute Error (MAE) and R² score. Gradient Boosting provided the lowest MAE and the highest R², making it the best model for the prediction task.

The Gradient Boosting model was selected as the best model based on its performance in both metrics:
MAE: 14.56
R² Score: 0.9802

## **Installation**

### **1. Clone the Repository**
git clone https://github.com/yourusername/ride-sharing-dynamic-pricing.git
cd ride-sharing-dynamic-pricing

### **2. Install Dependencies**
Make sure you have Python installed (>= 3.7). 
Install the required libraries:
pip install -r requirements.txt

### **3. Run the App**
Run the Dash app locally:
python app.py
The app will run at http://127.0.0.1:8050/.

## Acknowledgements
1. Dash by Plotly for building the interactive web application.
2. Scikit-learn and XGBoost for machine learning implementations.
3. Inspired by real-world applications in ride-sharing platforms.
