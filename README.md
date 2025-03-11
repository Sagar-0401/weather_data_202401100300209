# weather_data_202401100300209
Ai based weather monitoring system
# Weather Data Prediction

This project uses machine learning to predict weather-related variables such as Temperature, Humidity, and Rainfall. The model is trained using historical weather data and uses Linear Regression to make predictions. It also visualizes the predicted vs. actual values for each weather variable.

## Project Overview

The project includes the following steps:
1. **Data Loading**: Weather data is loaded from a CSV file.
2. **Data Preprocessing**: Missing values are handled and relevant features are selected.
3. **Feature Scaling**: The features are scaled using `StandardScaler` to ensure the model performs optimally.
4. **Model Training**: A Linear Regression model is trained on the preprocessed data.
5. **Prediction & Evaluation**: The model makes predictions and evaluates its performance using Mean Squared Error (MSE).
6. **Visualization**: Plots are generated to compare the actual vs. predicted values for Temperature, Humidity, and Rainfall.

## Requirements

Before running the code, make sure you have the following Python libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install these dependencies using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn
