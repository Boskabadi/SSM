# Soft Sensor Model (SSM)

This repository contains machine learning (ML) and deep learning (DL) models developed for predicting the Brix index using sensor data, including steam pressure, vacuum pressure, level, and time-series features. The repository consists of two Jupyter notebooks:

- SSM_ML.ipynb: Implements various ML models for different input configurations.
- SSM_DL.ipynb: Implements various DL architectures for more complex time-series data.
Project Overview
The goal is to accurately predict the Brix index using different combinations of sensor inputs across multiple models. The models are categorized into three configurations:

Model                        Type	ML Inputs	DL Inputs	Output
- Basic Model	Steam pressure,     Level	Steam pressure,     Level,  Time-series	Brix index
- Model 1	Vacuum pressure, Steam pressure, Level	Vacuum pressure, Steam pressure, Level, Time-series	Brix index
- Model 2 (Chosen)	Vacuum pressure, Steam pressure	Vacuum pressure, Steam pressure, Time-series	Brix index
Jupyter Notebooks
1. SSM_ML.ipynb (Sensor Simulation - Machine Learning)
This notebook explores traditional ML approaches, including Multiple Linear Regression (MLR), General Regression Neural Networks (GRNN), Support Vector Regression (SVR), and Decision Tree Regression (DTR).

Contents:
- Importing Data: Load and preprocess the dataset.
- Plotting Data: Visualize key trends in the sensor readings.
- MLR for Basic Model: Apply MLR using Steam pressure and Level.
- MLR for Model 1: Apply MLR using Vacuum pressure, Steam pressure, and Level.
- MLR for Model 2: Apply MLR using Vacuum pressure and Steam pressure.
- GRNN for Basic Model: Use GRNN for prediction with Basic model inputs.
- GRNN for Model 1: GRNN prediction using Model 1 inputs.
- GRNN for Model 2: GRNN prediction using Model 2 inputs.
- SVR for Basic Model: Apply SVR using Steam pressure and Level.
- SVR for Model 1: SVR prediction with Model 1 inputs.
- DTR for Model 2: Decision Tree Regression for Model 2 inputs.
- SVR for Model 2: Apply SVR with Model 2 inputs.
2. SSM_DL.ipynb (Sensor Sesnor Model - Deep Learning)
This notebook implements advanced deep learning architectures, including LSTM, GRU, and CNN, to capture time-series dependencies and improve predictive accuracy.

Contents:
-I mporting Data: Load and preprocess the dataset.
- Autocorrelation Function (ACF): Analyze time-series dependencies.
- LSTM for Basic Model: Apply LSTM using Steam pressure, Level, and Time-series.
- LSTM for Model 1: LSTM using Vacuum pressure, Steam pressure, Level, and Time-series.
- LSTM for Model 2: LSTM with Vacuum pressure, Steam pressure, and Time-series.
- GRU for Basic Model: GRU using Steam pressure, Level, and Time-series.
- GRU for Model 1: GRU using Model 1 inputs.
- GRU for Model 2: GRU with Model 2 inputs.
- CNN for Basic Model: CNN using Steam pressure, Level, and Time-series.
- CNN for Model 1: CNN using Model 1 inputs.
- CNN for Model 2: CNN using Model 2 inputs.


# Additional Information
- For more details on the process description and soft sensor, refer to the SSM article. [DOI: 10.1021/acs.iecr.4c03342](https://pubs.acs.org/doi/full/10.1021/acs.iecr.4c03342)
- For any questions or issues, please contact seso@kt.dtu.dk or morebo@kt.dtu.dk.
Thank you for using the SSM repository.
