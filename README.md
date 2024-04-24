# Li-ion Battery Remaining Useful Life Prediction

## Overview
This repository contains the implementation of a data-driven model for predicting the Remaining Useful Life (RUL) of Lithium-ion (Li-ion) batteries. Accurate prediction of RUL is crucial for assessing battery life and ensuring safe and reliable operation, particularly in applications such as electric vehicles (EVs).

## Methodology
The methodology employed in this study includes data collection, preprocessing, feature selection, and model development. The dataset used in this work consists of data from 14 NMC-LCO 18650 batteries, each with a nominal capacity of 2.8 Ah, subjected to more than 1000 charge-discharge cycles at a temperature of 25°C. 

## Data-Driven Models
Three different machine learning models were used for RUL prediction:
- Support Vector Regression (SVR) with linear kernel
- Support Vector Regression (SVR) with radial basis function (RBF) kernel
- Multilayer Perceptron (MLP) regression

## Results and Discussion
The performance of the models was evaluated using the Root Mean Square Error (RMSE), Mean Squared Error (MSE), and R² score. The MLP model demonstrated the lowest RMSE, indicating superior predictive accuracy compared to the SVR models.

## Conclusion 
In conclusion, this study presents a data-driven approach for accurately predicting the RUL of Li-ion batteries. The MLP model, in particular, showed promising results, highlighting the potential of machine learning in predictive maintenance and resource optimization for battery-dependent systems. Future work may involve further optimization of the models and exploration of additional features for improved prediction accuracy.

## Requirements
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- TensorFlow/Keras (for MLP model)
