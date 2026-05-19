# Real-Time Power Grid Monitoring and Energy Forecasting

## Overview

This project focuses on real-time energy demand forecasting and anomaly detection for power grid monitoring systems. The system analyzes electricity consumption data collected every 15 minutes and helps detect abnormal spikes or drops in energy usage.

The solution combines:

* Time Series Forecasting using SARIMAX
* Real-Time Anomaly Detection using Isolation Forest and LOF
* Data Visualization and Monitoring
* Continuous Model Evaluation

---

# Problem Statement

Power grid companies need to:

* Forecast future electricity demand accurately
* Detect unusual consumption behavior in real time
* Prevent outages and equipment failures
* Improve operational efficiency

The dataset contains:

* Timestamp
* Region
* Weather conditions
* Energy usage

---

# Objectives

* Forecast short-term energy demand
* Detect anomalies in streaming consumption data
* Monitor model performance continuously
* Support business decisions with real-time insights

---

# Technologies Used

| Category             | Tools/Libraries       |
| -------------------- | --------------------- |
| Programming Language | Python                |
| Data Processing      | Pandas, NumPy         |
| Visualization        | Matplotlib            |
| Forecasting          | Statsmodels (SARIMAX) |
| Anomaly Detection    | Scikit-learn          |
| ML Algorithms        | Isolation Forest, LOF |

---

# Workflow

```text
Streaming Energy Data
        ↓
Data Cleaning & Preprocessing
        ↓
Feature Engineering
        ↓
Anomaly Detection
        ↓
Time Series Forecasting
        ↓
Visualization & Alerts
        ↓
Performance Monitoring
```

---

# Anomaly Detection

## Isolation Forest

Isolation Forest is used to detect abnormal spikes or drops in electricity usage.

### Why Isolation Forest?

* Efficient for large datasets
* Fast anomaly detection
* Works well for real-time streaming systems

### Detects:

* Power spikes
* Sudden demand drops
* Equipment failures
* Sensor issues
* Power theft

---

## Local Outlier Factor (LOF)

LOF compares local density among neighboring points to identify local anomalies.

### Use Cases:

* Region-based abnormal behavior
* Local consumption irregularities
* Neighborhood anomaly analysis

---

# Forecasting Model

## SARIMAX Model

SARIMAX is used for short-term energy demand forecasting.

### Why SARIMAX?

Energy usage depends on:

* Trend
* Seasonality
* Weather conditions
* External factors

SARIMAX handles:

* Seasonal patterns
* Time dependencies
* External variables like temperature and humidity

---

# Model Validation

## Forecasting Metrics

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)

## Anomaly Detection Metrics

* Precision
* Recall
* False Alarm Rate

---

# Visualization

The project visualizes:

* Energy consumption trends
* Forecasted demand
* Detected anomalies
* Seasonal patterns

---

# Business Benefits

This solution helps power grid companies by:

* Improving energy demand planning
* Reducing operational costs
* Detecting faults early
* Preventing grid failures
* Supporting faster decision-making
* Improving power supply reliability

---

# Future Improvements

* Deploy real-time dashboards
* Add deep learning models like LSTM
* Integrate live weather APIs
* Implement automated alert systems
* Use Kafka or Spark Streaming for scalable real-time processing

---

# Conclusion

This project demonstrates how time series forecasting and anomaly detection can be combined to build an intelligent real-time power grid monitoring system. By using SARIMAX for forecasting and Isolation Forest/LOF for anomaly detection, the system improves operational efficiency, reliability, and decision-making in modern energy management systems.

---

# Author

Swarnima Srivastava
