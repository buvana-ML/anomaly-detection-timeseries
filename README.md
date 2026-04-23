# Time-Series Anomaly Detection using Isolation Forest

## Overview
This project focuses on detecting anomalies in time-series sensor data using an unsupervised machine learning approach.

## Approach
- Isolation Forest for anomaly detection
- Feature engineering:
  - Rolling mean
  - Rolling standard deviation
  - Temporal difference

## Results
- High recall (detected all anomalies)
- Improved precision through tuning
- Demonstrates precision-recall tradeoff

## Visual Results

### Before Tuning
(anomaly_plot_before.png)

### After Tuning
(anomaly_plot_after.png)

## Tech Stack
Python | Pandas | NumPy | Scikit-learn | Matplotlib

## Key Learnings
- Anomaly detection in noisy data is challenging
- Feature engineering is critical
- Trade-offs must be managed
