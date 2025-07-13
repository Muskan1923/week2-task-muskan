# 🌤️ Weather Data Analysis Tool

This project analyzes historical weather data (temperature and rainfall) for New Delhi using a CSV file from NOAA. It provides summary statistics, trends, and insights on extreme weather days.

---

## 📌 Features

- ✅ Load and clean daily weather data (`TMAX`, `TMIN`, `TAVG`, `PRCP`)
- 📊 Compute monthly and yearly summary statistics
- 🔥 Identify hottest and coldest days
- 🌦️ Analyze seasonal and yearly temperature/rainfall trends
- 📈 Visualize temperature trends over time using `Seaborn` and `Matplotlib`

---

## 📂 Dataset

- Source: [NOAA Climate Data Online](https://www.ncei.noaa.gov/cdo-web/datasets)
- Station: `IN022021900` (New Delhi Safdarjung, IN)
- Columns used:
  - `DATE`: Observation date
  - `TMAX`, `TMIN`, `TAVG`: Maximum, minimum, and average temperatures
  - `PRCP`: Precipitation

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-analysis-tool.git
   cd weather-analysis-tool

