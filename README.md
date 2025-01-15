# Dynamic Pricing for Ride-Sharing Services

## Overview
This project aims to develop a **Dash web application** that predicts ride prices using a trained **Gradient Boosting model**. The application allows users to input key factors such as distance, demand, time of day, and weather conditions to receive an accurate price prediction for the ride.  

The trained model was developed and evaluated on a dataset containing features like:
- Distance (in kilometers)
- Demand Index
- Time of Day (Morning, Afternoon, Evening, Night)
- Weather Conditions (Clear, Rainy, Snowy)

### Key Features:
1. **User Inputs**:
   - Distance (in kilometers)
   - Demand Index (1 to 10)
   - Time of Day (Morning, Afternoon, Evening, Night)
   - Weather (Clear, Rainy, Snowy)
2. **Price Prediction**:
   - The application computes the predicted ride price based on user inputs using the **Gradient Boosting model**.
3. **Integrated Execution**:
   - All functionality, including data loading, model training, and the Dash app, is embedded in a single Jupyter Notebook for simplicity.

---

## Model Evaluation
The **Gradient Boosting model** was selected as the optimal solution based on its superior performance metrics:
- **Mean Absolute Error (MAE)**: 14.56
- **R² Score**: 0.9802  

These metrics demonstrate the model's high accuracy and reliability in predicting ride prices.

---

## Usage
### To Run the Code:
1. Open dynamic_pricing_for_ride_sharing_services.ipynb in Google Colab or Jupyter Notebook.
2. Execute all the cells in the notebook sequentially.
3. The Dash web application will be hosted locally or via an external link if using Google Colab.
4. The prediction results and outputs can also be displayed directly in the notebook as part of the integrated execution.
   
### To Use the Application:
1.Enter the required inputs in the Dash app:
 - Distance (in kilometers)
 - Demand Index (rating from 1 to 10)
 - Time of Day (choose from Morning, Afternoon, Evening, Night)
 - Weather Conditions (choose from Clear, Rainy, Snowy)
2.Click the Predict button to view the predicted ride price in real-time.

---

## File Structure
The repository contains the following files:
- **`dynamic_pricing_for_ride_sharing_services.ipynb`**: containing all code for data loading, model training, Dash app setup, and execution
- **`ride_sharing.csv`**: Dataset used for model training and evaluation.
- **`README.md`**: This README file.
- **`LICENSE`**: Project license (MIT License).

---

## Acknowledgements
1. [Dash by Plotly](https://dash.plotly.com/) for creating the interactive web application.
2. [Scikit-learn](https://scikit-learn.org/) and [XGBoost](https://xgboost.readthedocs.io/) for machine learning implementations.
3. Inspired by real-world dynamic pricing strategies in ride-sharing platforms like Uber and Lyft.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

### Example Output
Below is an example of the predicted output from the application:

| **Inputs**            | **Predicted Price (₹)** |
|-----------------------|-------------------------|
| Distance: 10 km       |   303.87                |
| Demand Index: 8       |                         |
| Time of Day: Evening  |                         |
| Weather: Rainy        |                         |

![image](https://github.com/user-attachments/assets/c8169679-479b-40de-a037-80a9e4568190)


---

### Feedback & Contributions
Feel free to raise issues or contribute by submitting pull requests. Contributions are highly appreciated!
