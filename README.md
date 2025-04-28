# Anomaly Detection in NYC Taxi & Citi Bike Data (2024)

## Project Overview
This project analyzes daily trip data from New York City's Citi Bike and Yellow Taxi services for the year 2024. Time-series forecasting models (ARIMA and Prophet) were developed to predict expected trip volumes, and anomalies were identified based on deviations from these forecasts. The analysis explores correlations between anomalies, weather patterns, holidays, and day-of-week effects.

## Repository Structure
- `code/`: Python scripts and notebooks used for data processing, forecasting, and anomaly detection.
- `output/`: Generated figures, result CSVs, and interactive visualizations.
- `datasets/`: Dataset access information and Google Drive link.
- `report/`: Final project report (PDF will be added after completion).

## Key Components
- **Forecasting models:** ARIMA, Prophet
- **Anomaly detection methods:** Residual Z-Score Analysis, Interquartile Range (IQR), Seasonal-Trend Decomposition using Loess (STL)
- **Simulated weather analysis**
- **Interactive dashboard** (sample HTML output)

## Dataset Access
Due to large file sizes (~20GB+), raw datasets are not uploaded directly to GitHub.  
Access sources:
- [Citi Bike System Data](https://citibikenyc.com/system-data)
- [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

Processed datasets and project outputs are available here:  
- [Google Drive Folder](https://drive.google.com/drive/folders/1qXbdC3e2puORxVGPuOtaQilK5hYrYW98?usp=sharing)

## How to Use
1. Clone the repository.
2. Explore the code and outputs.
3. Review the report once uploaded.
4. (Optional) Re-run the analysis using the provided code and datasets.

## Author
Ahmet Mihca Aydin  
University of Connecticut  
Spring 2025
