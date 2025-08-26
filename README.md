# Numerical Analysis for Machine Learning Project 2023-2024
## Forecasting Spot Electricity Prices of Belgium: Deep Learning Approaches and Empirical Comparison of Traditional Algorithms.
This project reproduces and extends the findings from the paper: "Forecasting Short-Term Electricity Prices Using Deep Learning".

*The goal* is to explore different deep learning models for day-ahead electricity price forecasting, comparing their performance against traditional statistical methods. Accurate forecasting is crucial to adapt to the increasing integration of renewable energy sources into the electricity market.
- Investigate whether deep learning methods outperform traditional statistical models.
- Explore hybrid models combining multiple neural architectures.
- Benchmark models against baseline statistical approaches.

*Implemented Models:* The following models were implemented and tested:
- Deep Neural Network (DNN) – standard feedforward multilayer perceptron.
- Long Short-Term Memory (LSTM-DNN hybrid) – capturing temporal dependencies.
- Gated Recurrent Unit (GRU-DNN hybrid) – recurrent model for sequence data.
- Convolutional Neural Network (CNN) – extracting local temporal patterns.
- Multi-Layer Perceptron (MLP) – as statistical benchmark.
- Support Vector Regression (SVR) – classical machine learning baseline.

*Dataset:* EARN dataset (electricity price data) - Predict the day-ahead electricity price for each hour, using only the information available up to the previous day.
