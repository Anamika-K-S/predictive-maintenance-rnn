# Aircraft Engine Predictive Maintenance using RNN

## Overview
This project implements a predictive maintenance framework for aircraft engines using
recurrent neural networks (RNNs). Multivariate time-series sensor data is used to predict
whether an engine will fail within a predefined prediction window.

The solution follows an end-to-end machine learning pipeline including data preprocessing,
sequence generation, model training, and evaluation on unseen test data.

---

## Dataset
The dataset was obtained from Kaggle and contains simulated aircraft engine sensor readings.

- Training, test, and ground-truth files are provided separately
- Each engine consists of multiple operational cycles
- 21 sensor measurements and 3 operational settings are recorded per cycle

Dataset link:
https://www.kaggle.com/datasets/maternusherold/pred-maintanance-data

---

## Project Structure
predictive-maintenance-rnn/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── raw
│     └── PM_test.txt
│     └── PM_train.txt
│     └── PM_truth.txt
│
├── notebooks/
│   └── predictive_maintenance_rnn.ipynb
│
├── models/
│   └── rnn_model.keras
│
└── results/
    └── plots/
