# Time Series Analysis Projects (STAT 153 - UC Berkeley)

This repository contains a collection of time series analysis projects completed as part of the course **STAT 153: Introduction to Time Series** at **UC Berkeley**. Each project applies a different class of time series models or techniques to real or simulated data, covering both classical statistical methods and modern approaches.

## Repository Structure

The repository includes the following Jupyter notebooks:

### 📁 [proj01_multiple_linear_model.ipynb](./proj01_multiple_linear_model.ipynb)
**Topic**: Multiple Linear Regression for Time Series  
- Applied multiple linear regression to model time series data with deterministic components.
- Included lagged variables and time trends as predictors.
- Demonstrated understanding of residual analysis, interpretation of model coefficients, and basic forecasting.

### 📁 [proj02_spectral_analysis.ipynb](./proj02_spectral_analysis.ipynb)
**Topic**: Sinusoidal Model Fitting, Spectral Analysis and Fourier Methods  
- Conducted sinusoidal model fitting for time series analysis.
- Used **Fourier transformations** and **spectral density estimation** to analyze cyclical components in time series data.
- Interpreted periodograms and smoothed spectra to detect dominant frequencies.
- Applied windowing techniques and discussed the effects of aliasing and leakage.

### 📁 [proj03_changepoint_regularization.ipynb](./proj03_changepoint_regularization.ipynb)
**Topic**: Change Point Detection and Piecewise Models  
- Detected **structural breaks** in time series using change point analysis.
- Built **piecewise linear models** to capture changes in trend.
- Explored **regularization techniques** (such as ridge regression) to stabilize estimation under multicollinearity and overfitting.

### 📁 [proj04_autoregressive_model.ipynb](./proj04_autoregressive_model.ipynb)
**Topic**: Autoregressive (AR) Models  
- Estimated and validated **AR(p)** models.
- Evaluated stationarity, ACF/PACF plots, and used **Yule-Walker equations**.
- Compared model orders using information criteria (AIC/BIC) and forecast accuracy.

### 📁 [proj05_arima_seasonal.ipynb](./proj05_arima_seasonal.ipynb)
**Topic**: ARIMA and Seasonal ARIMA Models  
- Fitted **ARIMA** and **SARIMA** models to both simulated and real-world data.
- Applied **differencing** to achieve stationarity.
- Conducted model diagnostics and generated multi-step ahead forecasts.

## Key Skills Demonstrated

- 📈 **Model Fitting**: Experience fitting regression-based and stochastic models to time series data.
- ⚙️ **Spectral Analysis**: Proficient in interpreting and applying Fourier-based methods.
- 🔀 **Change Point Analysis**: Detecting structural changes and adapting models accordingly.
- 🔁 **ARIMA Modeling**: Full pipeline from model identification to validation and forecasting.
- 💻 **Recurrent Neural Network (RNN)**: Applied RNN models such as long short term memory (LSTM), gated recurrent unit (GRU) for forecasting.
- 🧠 **Regularization Techniques**: Applying penalization methods to control model complexity.

## Technical Stack

- **Python** (Jupyter notebooks)
- **NumPy**, **Pandas**, **Matplotlib**, **Statsmodels**, **SciPy**, **Scikit-Learn**, **PyTorch**

## How to Use

Clone the repository and open any notebook in JupyterLab or Jupyter Notebook:

```bash
git clone https://github.com/RichardYuan04/TimeSeriesAnalysis.git
cd TimeSeriesAnalysis
jupyter lab  # or jupyter notebook
```

📄 Note: The original project instruction files have been removed from the repository due to course material regulation issues.
If you need access to them, feel free to contact me or raise an issue.

## About
This repository reflects my learning journey through UC Berkeley's STAT 153 course, emphasizing both theoretical understanding and practical implementation of core time series methods.
I shall express sincere thankfulness and appreciation for Professor Aditya Guntuboyina's clear, elaborate and excellent instructions on the selected topics of Time Series Analysis.


