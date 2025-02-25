# N-Beats Time-Series Forecasting Training

This repository contains a Jupyter Notebook that demonstrates how to train a time-series forecasting model using the N-Beats architecture with the Darts library. This notebook uses Python and various libraries for machine learning and time-series forecasting.

## Table of Contents

1. [Installation](#installation)
2. [Data Preprocessing](#data-preprocessing)
3. [Model Training](#model-training)
4. [Evaluation](#evaluation)
5. [TensorBoard Logging](#tensorboard-logging)

## Installation

To run the notebook, you must first install the required dependencies. You can install them using `pip`:

```bash
pip install darts
```
Data Preprocessing
In this section, the notebook demonstrates how to load, clean, and preprocess the time-series data. Preprocessing includes handling missing values, transforming the data into the correct format, and splitting it into training and testing sets.

Model Training
The notebook shows how to set up and train the N-Beats model for time-series forecasting using the Darts library. You will also see how to set training parameters such as the number of epochs and batch size.

Evaluation
After training the model, the notebook evaluates the performance of the forecast by comparing it to the test data using various metrics, such as MAE, RMSE, etc.
