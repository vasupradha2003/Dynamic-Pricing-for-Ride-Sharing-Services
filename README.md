# Dynamic Pricing for Ride-Sharing Services 🚗💸

This project demonstrates how to build a **Dynamic Pricing System** for ride-sharing services using multiple machine learning algorithms and a web-based user interface powered by Dash. 

The system predicts ride prices dynamically based on features such as distance, time of day, demand, and weather conditions, leveraging machine learning models to optimize predictions.

---

## **Project Features**

### **1. Data Simulation**
- A synthetic dataset is generated with 1000 samples, containing:
  - `Distance` (in km)
  - `Time of Day` (Morning, Afternoon, Evening, Night)
  - `Demand` Index (1 to 10)
  - `Weather` (Clear, Rainy, Snowy)
- Dynamic pricing is calculated using custom multipliers based on time of day and weather.

### **2. Machine Learning Workflow**
- Trains and evaluates multiple models:
  - **Random Forest Regressor**
  - **Linear Regression**
  - **Gradient Boosting Regressor**
  - **XGBoost Regressor**
- Evaluates models using metrics:
  - **Mean Absolute Error (MAE)**
  - **R² Score**
- Selects the **best model** for predictions based on performance.

### **3. Interactive Dashboard**
- Built using **Dash** to provide a user-friendly interface for real-time predictions.
- Users can input:
  - Distance (in km)
  - Demand Index
  - Time of Day
  - Weather
- Displays predicted ride price dynamically.

---

## **Installation**

### **1. Clone the Repository**
```bash
git clone https://github.com/<username>/<repository-name>.git
cd <repository-name>
```
### **2. Install Dependencies**
Make sure you have Python installed (>= 3.7). 
Install the required libraries:
pip install -r requirements.txt
### **3. Run the App**
Run the Dash app locally:
python app.py
The app will run at http://127.0.0.1:8050/.

----
## Acknowledgements
1. Dash by Plotly for building the interactive web application.
2. Scikit-learn and XGBoost for machine learning implementations.
3. Inspired by real-world applications in ride-sharing platforms.
