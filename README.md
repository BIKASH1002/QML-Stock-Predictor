# Overview

This project explores the integration of Quantum Machine Learning (QML) to enhance stock market prediction accuracy. Quantum computing offers significant advantages over classical methods, particularly in handling complex, high-dimensional datasets. The research applies quantum regression models using Qiskit and Pennylane to predict stock prices, demonstrating the potential of quantum algorithms in financial forecasting.

# Problem Statement

Stock market prediction is inherently challenging due to its non-linear and volatile nature. Traditional machine learning models struggle with the extensive datasets and intricate patterns in financial data. This project leverages quantum computing principles like superposition and entanglement to develop more sophisticated predictive models that can capture hidden correlations and improve forecasting accuracy.

# Methodology

The approach involves using Quantum Linear Regression models for predicting stock prices. The dataset, which includes attributes such as Open, High, Low, Close, Adjusted Close, and Volume, is pre-processed and converted into quantum states for processing through quantum circuits. The workflow includes feature selection, quantum encoding, simulation, and performance analysis.

# Data Pre-processing

The dataset used in this project is a standard stock market dataset, obtained from platforms like Kaggle, consisting of 3369 rows of data. The attributes include:

Date

Open

High

Low

Close

Adjusted Close

Volume

Data pre-processing involves imputing missing values, scaling, and feature selection using a correlation matrix. The data is then encoded into quantum states using a feature map encoder that applies Hadamard and Controlled-Z gates.

# Quantum Circuit Design

**Feature Map Encoding:** Uses Hadamard gates for superposition and Controlled-Z gates for entanglement.

**Quantum Linear Regression Algorithm:** Processes the encoded quantum states to predict stock prices.

**Simulator:** Simulates the quantum circuit using Qiskit, enabling visualization and analysis of performance metrics.

# Performance Metrics

Mean Square Error (MSE)

Root Mean Square Error (RMSE)

Mean Absolute Error (MAE)

R-Squared (R²) Score

# Results

| Performance Metrics                    | Result  |
|----------------------------------------|---------|
| Mean square error (MSE)                | 1.91%   |
| Root mean square error (RMSE)          | 13.84%  |
| Mean absolute error (MAE)              | 9.33%   |
| R² test                                | 0.68    |

# Future Scope

Quantum Machine Learning is still in its developmental phase, and the current model can be enhanced by integrating sentiment analysis and expanding feature selection. As quantum computing technologies advance, real-time deployment of these models on quantum devices could revolutionize financial forecasting.
