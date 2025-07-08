# ottawa_weather

## 🌦️ Weather Forecasting & Analysis Script Overview

This Python script performs the following tasks:

- 📥 Downloads weather data from [climate.weather.gc.ca](https://climate.weather.gc.ca) for Ottawa station **4333**.
- 📊 Plots historical temperature data including:
  - Aggregate **monthly** mean temperatures.
  - Aggregate **yearly** mean temperatures.
- 🔮 Predicts daily mean temperatures using **PyTorch** and an **LSTM (Long Short-Term Memory)** model.
- 📈 Calculates and plots **1-year** and **10-year rolling means** to observe long-term trends.
- 🔥 Generates a **correlation heatmap** to visualize relationships between monthly **minimum temperatures**.

