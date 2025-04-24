# 🌾 Crop Yield Prediction with AI Under Data Quality Challenges

This repository contains code and resources for the paper:
**"Robust Yield Prediction in Precision Agriculture Using AI with Simulated Data Quality Issues"**, prepared for submission to the IEEE J-STARS Special Issue on *Data Quality Issues and Solutions in AI-based Remote Sensing Applications*.

## 📌 Project Overview

This project explores the application of **Random Forest** and **XGBoost** regression models to predict crop yield using multi-source remote sensing and soil data. It specifically investigates the **impact of data quality issues**, such as:
- Missing vegetation index values (e.g., NDVI),
- Sensor misalignment in temporal GPP signals.

## 🧠 Key Features

- 📊 **Random Forest & XGBoost** yield prediction
- 🌱 **Time-series GPP, NDVI, EVI**, and soil features
- ⚠️ **Simulated data quality issues**:
  - Missing NDVI (`20%` random masking)
  - Misalignment in GPP time steps
- 📉 Robust performance evaluation using:
  - RMSE
  - R² Score
  - Residual distributions
- 🔍 Feature importance and correlation analysis

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/ai-yield-prediction-quality.git
cd ai-yield-prediction-quality

