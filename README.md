
# AQI-Forecasting

**AQI Forecasting using Machine Learning and Spatio-Temporal Graph Neural Networks**

M.Tech Thesis Project — Indian Institute of Information Technology Lucknow  
Author: Mayank Kapgate (MCS25040)  
Supervisor: Dr. Saurabh Shukla | Co-Supervisor: Dr. Shiladitya Bhattacharjee

---

## Overview

This project implements a **Dynamic Agentic Spatio-Temporal Graph Convolutional Network (DA-STGCN)**
for urban Air Quality Index (AQI) / PM2.5 forecasting across 12 monitoring stations in Beijing.

## Models Compared

| Model | Avg MAE | Avg R² |
|---|---|---|
| RandomForest | 6.57 | 0.9708 |
| XGBoost | 6.99 | 0.9673 |
| LightGBM | 7.06 | 0.9676 |
| GradientBoosting | 7.02 | 0.9694 |
| ST-Graph | 10.76 | 0.9380 |
| **Stack (Best)** | **7.01** | **0.9724** |

## Dataset

Beijing Multi-Site Air Quality Dataset (UCI)  
12 stations, 2013–2017, hourly readings.  
Download: https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data

## Setup

```bash
pip install -r requirements.txt
```

Open `notebooks/aqi_forecasting.ipynb` in Jupyter or Google Colab.

## Results

All output plots and the scoreboard CSV are in the `results/` folder.

## License

MIT
