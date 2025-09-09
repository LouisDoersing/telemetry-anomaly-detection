
# Satellite Telemetry Anomaly Detection

This project develops a machine learning pipeline for **anomaly detection in satellite/rocket telemetry data**.  
It uses **time-series forecasting** and **reconstruction models** (TCN, Autoencoder, Transformer) to identify unusual patterns in multivariate telemetry streams.

## Features
- Data preprocessing (scaling per unit, windowing, missing/outlier handling)
- Forecasting-based anomaly scoring
- Autoencoder reconstruction error scoring
- Hybrid ensemble anomaly detection
- Evaluation with NAB score, AUC-PR, latency penalty
- Deployment: FastAPI + Plotly Dash Dashboard
- Experiment tracking with MLflow, data versioning with DVC

## Project Structure
