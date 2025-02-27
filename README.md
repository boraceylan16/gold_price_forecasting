# Gold Price Forecasting with PCA and LSTM

## Project Overview
This project aims to predict future gold prices using a combination of **Principal Component Analysis (PCA)** for dimensionality reduction and **Long Short-Term Memory (LSTM)** networks for time series forecasting. By leveraging historical gold price data, the project explores how machine learning techniques can be applied to forecast trends in a volatile market.

### Objectives:
- Forecast future gold prices.
- Apply dimensionality reduction techniques (PCA) to simplify the data.
- Use LSTM to capture temporal dependencies in the time series data.
- Evaluate the model’s performance using standard metrics such as RMSE and MAE.

## Technologies Used
- **NumPy**: Numerical computing.
- **Pandas**: Data manipulation and analysis.
- **scikit-learn**: For PCA and preprocessing.
- **Keras/TensorFlow**: For building and training the LSTM model.
- **Matplotlib/Seaborn**: Data visualization.

## Project Steps
### 1. Data Collection & Preprocessing
The first step involved gathering historical gold price data, handling missing values, and standardizing the features for better model performance.

### 2. Dimensionality Reduction with PCA
PCA was used to reduce the dimensionality of the dataset by identifying the most critical features that explain the variance in gold price movements.

### 3. Time Series Forecasting with LSTM
An LSTM model was used to predict future gold prices by capturing the temporal dependencies in the time series data.

### 4. Model Evaluation
The performance of the model was evaluated using metrics such as MSE (Mean Squared Error) and MAPE (Mean Absolute Percentage Error). The predicted prices were compared with the actual gold prices for evaluation.
