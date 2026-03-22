# Time-Series-Prediction-Model-Storm-Events
This project implements a time series forecasting model to predict future storm events using historical data from 1950 to 2020.
# Tools & Libraries
- Google colab
- Python
- Pandas & NumPy
- TensorFlow / Keras (LSTM, Bi-LSTM)
- ESN (Echo State Network)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Data preprocessing & metrics)
# How I Built It
1. Collected and combined storm events data from 1950 to 2020.
2. Selected relevant features: date, magnitude, event type, latitude, longitude.
3. Filled missing values and removed invalid dates.
4. Created new features: year, month, day.
5. Scaled numerical features using MinMaxScaler.
6. Built LSTM and Bi-LSTM models using TensorFlow/Keras.
7. Trained models and validated performance using RMSE, MAE, and R² metrics.
8. Implemented an Echo State Network (ESN) model for comparison.
9. Visualized actual vs predicted values using Matplotlib and Seaborn.
