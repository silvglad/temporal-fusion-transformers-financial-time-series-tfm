# TFM - Temporal Fusion Transformer for Financial Time Series Forecasting

This repository contains the source code, Jupyter notebooks, and experiments developed as part of my Master’s Final Thesis (TFM), focused on the implementation and evaluation of the **Temporal Fusion Transformer (TFT)** architecture for financial time series forecasting. The project specifically targets the prediction of the **IBEX 35** index, leveraging both traditional and deep learning-based approaches for comparison.

## Repository Structure

The repository contains the most relevant experiments and results of the thesis, as the entire experimentation would be too large to be included. The notebooks are organized between those done in Darts and those done in Pytorch, as well as the one based on model comparison.

## Objectives

The objective of this work is to:

- Implement and understand the **Temporal Fusion Transformer** architecture.
- Apply the model to real financial data (IBEX 35 index).
- Compare the TFT’s performance against:
  - Classical statistical models: ARIMA, Prophet
  - Deep learning approaches: LSTM
- Interpret the results and evaluate the model's explainability capabilities.

## Dataset

- **Source:** Financial data retrieved via `Yahoo Finance` API.
- **Target:** Daily closing prices of the IBEX 35 index.
- **Features:** Technical indicators (MACD, RSI, Bollinger Bands, etc.), calendar covariates (weekday, month, holidays), and component weights. All this for IBEX 35 stocks as well as other exogenous variables such as the S&P 500 index.


## Main Technologies Used

- Python 3.10+ (+ Numpy, Pandas, Matplotlib, Seaborn, etc.)
- Jupyter Notebooks (via Google Colab)
- [Darts](https://github.com/unit8co/darts)
- [PyTorch Forecasting](https://github.com/jdb78/pytorch-forecasting)
- TensorBoard
- PygWalker
- Optuna

## Author
TFM - UAX Master in Artificial Intelligence \
Enrique Caballero Muñoz
Consult paper on [LinkedIn](https://www.linkedin.com/in/enrique-caballero-muñoz-6297a8281/)
