# Haressing Quantum Computing for Stock Market Prediction

<div  align = "justify">
    
# Overview

This project explores the integration of Quantum Machine Learning (QML) to enhance stock market prediction accuracy. Quantum computing offers significant advantages over classical methods, particularly in handling complex, high-dimensional datasets. The research applies quantum regression models using Qiskit and Pennylane to predict stock prices, demonstrating the potential of quantum algorithms in financial forecasting.

# Problem Statement

Stock market prediction is inherently challenging due to its non-linear and volatile nature. Traditional machine learning models struggle with the extensive datasets and intricate patterns in financial data. This project leverages quantum computing principles like superposition and entanglement to develop more sophisticated predictive models that can capture hidden correlations and improve forecasting accuracy.

# Data Understanding

The dataset used for this project is a standard stock market dataset, containing historical data for various stocks, with attributes such as:

Date

Open

High

Low

Close

Adjusted Close

Volume

This dataset contains 3369 rows and is well-suited for stock market prediction tasks due to the availability of historical data points that exhibit trends, seasonality and volatility which are essential factors for time series analysis.

# Methodology

The approach involves using Quantum Linear Regression models for predicting stock prices. The dataset, which includes attributes such as Open, High, Low, Close, Adjusted Close and Volume, is pre-processed and converted into quantum states for processing through quantum circuits. The workflow includes feature selection, quantum encoding, simulation and performance analysis.

# Setup

Jupyter Notebook (for interactive development) or IBM notebook

**Libraries:** numPy, pandas, matplotlib, scikit-learn, qiskit

qiskit library need to be installed in order to execute quantum functions.

# Establishing Quantum Circuit

**1) Feature Map Encoding:** Uses Hadamard gates for superposition and Controlled-Z gates for entanglement.

**2) Quantum Linear Regression Algorithm:** Processes the encoded quantum states to predict stock prices.

**3) Simulator:** Simulates the quantum circuit using Qiskit, enabling visualization and analysis of performance metrics.

</div>

# Design

<p align="center">
    <img src="https://github.com/user-attachments/assets/564a2a97-24d2-47a3-81fd-8c4b8b41c751" alt="Flow diagram"/>
</p>

# Implementation

**1) Data Preprocessing:**
Handle missing values through imputation and normalize data. Perform feature selection using correlation matrix.

**2) Quantum Data Encoding:**
Convert classical data into quantum states using a feature map encoder. Apply gates like Hadamard (for superposition) and Controlled-Z (for entanglement).
Visualize encoded data using a Bloch sphere.

**3) Quantum Circuit Design:**
Design the quantum circuit for quantum linear regression using rotation gates (Pauli-X, Y, Z). Integrate parameterized quantum circuits (variational ansatz) for cost function optimization.

**4) Model Training:**
Split data into training (80%) and testing (20%) sets. Train the model using quantum linear regression on a quantum circuit simulator.

**5) Model Evaluation:**
Evaluate performance using metrics: Mean Square Error (MSE), Mean Absolute Error (MAE) and R-squared (R²).

# Results

<div align="center">

| Performance Metrics                    | Result  |
|----------------------------------------|---------|
| Mean square error (MSE)                | 1.91%   |
| Root mean square error (RMSE)          | 13.84%  |
| Mean absolute error (MAE)              | 9.33%   |
| R² test                                | 0.68    |

</div>

**GRAPHICAL ANALYSIS**

<table>
    <tr>
        <td>
            <img src="https://github.com/user-attachments/assets/9d7d2655-5301-430d-9446-34781784e654" alt="Objective Function" width="300">
            <p align="center">Objective Function</p>
        </td>
        <td>
            <img src="https://github.com/user-attachments/assets/5f03d990-e8e9-4896-bd23-b48b9e06539e" alt="Error Distribution" width="300">
            <p align="center">Error Distribution</p>
        </td>
        <td>
            <img src="https://github.com/user-attachments/assets/8334d31a-deb5-4c1d-b622-bf5f23f18923" alt="R2 value" width="300">
            <p align="center">Coefficient of Determination</p>
        </td>
    </tr>
</table>

# Conclusion

<div  align = "justify">
Though the knowledge of quantum computing and its algorithms are in development phase but it is also true that the idea of using it in prediction of stock holds promise. The error we achieved i.e., 1.9% might be less and hence certainly could be used for prediction of stock but this could be improved further if we could bring this error to less than 1% by optimising the algorithm. 
</div>

# Credits

**1) Dataset link:** https://www.kaggle.com/datasets/mattiuzc/stock-exchange-data
 
**2) Guide:**
Dr. Sandeep Kumar Satapathy, Professor, Vellore Institute of Technology, Chennai
