# Synthetic Multivariate Time Series Data Generation and Anomaly Detection

This repository contains a Python script to generate synthetic multivariate time series data for hardware monitoring metrics such as CPU temperature, usage, load, memory usage, battery level, and CPU power. The script introduces random anomalies in the data, making it suitable for testing anomaly detection algorithms.

## Features

- **Data Collection**: Simulates real-time hardware monitoring data over a specified duration.
- **Metrics Included**:
  - CPU Temperature
  - CPU Usage
  - CPU Load
  - Memory Usage
  - Battery Level
  - CPU Power
- **Anomaly Injection**: Random anomalies (e.g., high CPU usage, high temperature, etc.) are introduced to create realistic scenarios.
- **Storage**: Saves the generated data to a CSV file for further analysis.
- **Visualization**: Includes anomaly detection and visualization to highlight anomalies in the dataset.

## Requirements

- Python 3.x
- Libraries:
  - `wmi`
  - `psutil`
  - `pandas`
  - `datetime`
  - `time`
  - `random`

Install the dependencies using:
```bash
pip install wmi psutil pandas
