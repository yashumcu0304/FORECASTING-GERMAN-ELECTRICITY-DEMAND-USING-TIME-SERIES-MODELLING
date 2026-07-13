# Energy Forecast Lab: Electricity Demand Forecasting

## Overview

This repository contains a complete end-to-end implementation of an electricity demand forecasting project developed as part of an academic time series forecasting assignment. The project investigates multiple forecasting approaches ranging from classical statistical models to machine learning and deep learning techniques, with the goal of accurately predicting German electricity demand.

The notebook follows a structured data science workflow that includes data preprocessing, exploratory analysis, stationarity testing, model development, forecasting, performance evaluation, and comparative analysis.

---

## Dataset

The project uses historical German electricity demand data obtained from the Open Power System Data (OPSD) repository.

The dataset is processed to support multiple forecasting approaches through:

- Data cleaning
- Missing value handling
- Time index validation
- Weekly and monthly resampling
- Feature preparation
- Time series visualization

Temperature data is also incorporated as an external variable for multivariate forecasting using the SARIMAX model.

---

## Project Workflow

The notebook is organized into the following stages:

1. Environment setup
2. Library installation and imports
3. Project configuration
4. Data loading and preprocessing
5. Weekly and monthly resampling
6. Exploratory data visualization
7. Seasonal decomposition
8. Stationarity analysis
9. Train-test split
10. Evaluation utilities
11. Manual SARIMA parameter search
12. SARIMA forecasting
13. Residual diagnostics
14. Temperature data integration
15. SARIMAX forecasting
16. Machine learning forecasting
17. Hourly LSTM data preparation
18. LSTM model training
19. LSTM evaluation
20. Final model comparison
21. Export of results and trained models

---

## Forecasting Models

### Benchmark Models

- Mean Forecast
- Naïve Forecast
- Seasonal Naïve Forecast
- Drift Forecast

### Statistical Models

- SARIMA
- SARIMAX with Temperature as an Exogenous Variable

### Machine Learning Models

- Random Forest Regressor
- Gradient Boosting Regressor

### Deep Learning Model

- Long Short-Term Memory (LSTM)

---

## Key Features

- Complete preprocessing pipeline
- Exploratory Data Analysis (EDA)
- Weekly and monthly time series aggregation
- Seasonal decomposition
- Stationarity testing using the Augmented Dickey-Fuller (ADF) test
- Manual SARIMA grid search using AIC
- Confidence interval forecasting
- Residual diagnostics
- SARIMAX implementation with temperature data
- Feature-based machine learning models
- Hourly LSTM forecasting
- Comparative performance evaluation
- Forecast visualization
- Export of trained models and results

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn
- TensorFlow / Keras
- Joblib

---

## Evaluation Metrics

The forecasting models are evaluated using the following performance metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

These metrics are used to compare forecasting accuracy across statistical, machine learning, and deep learning models.

---

## Repository Structure

```
├── Energy_Forecast_Lab_Colab_Assignment_Ready.ipynb
├── dataset/
├── models/
├── results/
├── images/
├── README.md
└── requirements.txt
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Navigate to the project directory

```bash
cd your-repository-name
```

### 3. Install the required dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and execute each cell in sequence.

---

## Project Highlights

- End-to-end electricity demand forecasting workflow
- Manual SARIMA hyperparameter optimization
- Confidence interval prediction
- Residual analysis for statistical validation
- Multivariate forecasting using temperature data
- Machine learning regression models
- Hourly deep learning forecasting using LSTM
- Comprehensive comparison of forecasting approaches
- Exportable models and forecasting results

---

## Results

The project compares benchmark forecasting methods, statistical models, machine learning algorithms, and deep learning models to determine the most effective approach for electricity demand prediction.

The comparative evaluation provides insights into model accuracy, robustness, and practical suitability for real-world energy forecasting applications.

---

## Learning Outcomes

This project demonstrates practical experience in:

- Time series forecasting
- Statistical modelling
- Feature engineering
- Machine learning
- Deep learning
- Forecast evaluation
- Data visualization
- Model comparison
- Energy demand analytics

---

## Future Improvements

Future enhancements could include:

- Automated hyperparameter optimization
- Holiday and calendar feature integration
- Additional weather variables
- Transformer-based forecasting architectures
- Probabilistic forecasting
- Real-time prediction pipeline
- Model deployment using cloud services

---

## Author

**Sanjay Sahoo**

This project was developed as part of an academic assignment to explore and compare statistical, machine learning, and deep learning techniques for electricity demand forecasting.

---

## License

This repository is intended for educational, research, and learning purposes.
