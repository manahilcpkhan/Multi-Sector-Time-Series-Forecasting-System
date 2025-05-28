# Multi-Sector Time Series Forecasting System 📈🔮

A comprehensive web-based forecasting platform that implements and compares multiple time series models across Finance, Energy, and Environmental sectors with an interactive React dashboard for real-time predictions and analysis.

## 🎯 Project Overview

This system provides comparative analysis of various forecasting models including ARIMA, ANN, SARIMA, Prophet, LSTM, and hybrid approaches across different sectors to deliver accurate time series predictions through an intuitive web interface.

## ✨ Key Features

- **Multi-Sector Analysis**: Finance (S&P 500), Energy (consumption), Environmental (CO2) data
- **7 Forecasting Models**: ARIMA, ANN, SARIMA, ETS, Prophet, SVR, LSTM, Hybrid ARIMA-ANN
- **Interactive Dashboard**: Real-time model comparison and visualization
- **Model Performance Metrics**: Accuracy, residuals, and comparative analysis
- **Data Upload & Retraining**: Dynamic model updating with new datasets

## 🛠️ Technology Stack

### Backend
- **Python Flask** - API and server-side logic
- **SQLite** - Data storage and results management
- **Pandas/NumPy** - Data preprocessing and analysis
- **Statsmodels** - ARIMA and statistical models
- **TensorFlow/Keras** - Neural network implementations
- **Scikit-learn** - SVR and model evaluation

### Frontend
- **ReactJS** - Dynamic user interface
- **Chart.js/D3.js** - Interactive data visualizations
- **HTML/CSS** - Responsive design and styling

## 📊 Forecasting Models

### Traditional Models
- **ARIMA**: Autoregressive Integrated Moving Average for linear patterns
- **SARIMA**: Seasonal ARIMA for seasonal time series
- **ETS**: Exponential Smoothing for trend and seasonality
- **Prophet**: Facebook's model for multiple seasonality patterns

### Machine Learning Models
- **ANN**: Artificial Neural Networks for nonlinear relationships
- **SVR**: Support Vector Regression with kernel functions
- **LSTM**: Long Short-Term Memory for sequence prediction
- **Hybrid ARIMA-ANN**: Combined linear and nonlinear modeling

## 🗃️ Data Sources

- **Finance Sector**: Monthly S&P 500 stock prices
- **Energy Sector**: Hourly energy consumption data
- **Environmental Sector**: Daily atmospheric CO2 concentrations

## 🚀 Installation & Setup

```bash
# Clone repository
git clone https://github.com/yourusername/forecasting-system.git
cd forecasting-system

# Backend setup
cd backend
pip install -r requirements.txt
python app.py

# Frontend setup
cd frontend
npm install
npm start

# Access application at http://localhost:3000
```

## 💻 Usage

1. **Select Sector**: Choose Finance, Energy, or Environmental data
2. **Choose Models**: Select forecasting models for comparison
3. **View Predictions**: Analyze forecasts with interactive charts
4. **Compare Performance**: Side-by-side model accuracy metrics
5. **Upload Data**: Add new datasets for model retraining

## 📈 Dashboard Features

- **Model Selection Dropdown**: Choose from 7+ forecasting models
- **Real-time Visualization**: Dynamic charts updating with predictions
- **Performance Metrics**: Accuracy, RMSE, MAE comparison tables
- **Residual Analysis**: Model error visualization and statistics
- **Data Upload Interface**: CSV file upload for custom forecasting

## 🎯 Model Performance Targets

- **95%+ Accuracy**: Optimal performance (20/20 points)
- **85-95% Accuracy**: Good performance (15/20 points)
- **80-85% Accuracy**: Acceptable performance (10/20 points)
- **70-80% Accuracy**: Below expectations (5/20 points)
- **<70% Accuracy**: Insufficient performance (0/20 points)

## 🏆 Key Achievements

- Successfully implemented 7+ different forecasting models
- Created responsive React-based dashboard
- Integrated multi-sector time series analysis
- Built hybrid model combining ARIMA and ANN approaches
- Developed real-time model comparison capabilities

## 📊 Data Preprocessing Pipeline

1. **Data Cleaning**: Missing value imputation and outlier removal
2. **Normalization**: Scaling data to uniform ranges
3. **Stationarization**: Differencing and log transformations
4. **Feature Engineering**: Creating relevant input features for models

---

*A comprehensive forecasting platform demonstrating advanced time series modeling, machine learning integration, and full-stack web development skills.*