# 🌍 Climate Crisis Dashboard using R Shiny

This interactive R Shiny dashboard visualizes key insights related to the climate crisis.  
It includes global temperature trends, CO₂ emission patterns, national sustainability scores, and a forecast of South Korea’s path toward carbon neutrality.

---

## 🚀 Live App  
👉 [Click to Open Dashboard](https://juhee091.shinyapps.io/climatecrisis/)

---

## 📊 Features

### 🌡️ Temperature vs CO₂ Emissions
- Shows the correlation between global temperature anomalies and average CO₂ emissions over time.
- ✅ Finding: A strong positive correlation indicates human-driven climate change.

### 🌱 Country Sustainability Score
- Compares countries based on:
  - Renewable energy share
  - Per capita CO₂ emissions
  - Carbon efficiency (GDP per unit CO₂)
- ✅ Finding: Countries with higher scores are more climate-resilient.

### 🇰🇷 Korea’s CO₂ Emissions Forecast
- Uses the Prophet time-series model to predict South Korea's CO₂ emissions until 2050.
- ✅ Finding: Based on current trends, Korea needs stronger climate policies to meet its net-zero goal.

---

## 🛠️ Tech Stack

- **R** (ggplot2, dplyr, prophet, shiny)
- **Data Sources**:
  - NASA GISTEMP
  - Our World in Data (OWID)
  - UN SDG indicators

---

## 📁 Project Structure

```
climate-crisis-dashboard/
├── app.R
├── eda.R
├── analysis1_temp_co2.R
├── analysis2_sustain_score.R
├── analysis3_korea_forecast.R
├── GLB.Ts+dSST.csv
├── owid-co2-data.csv
├── owid-energy-data.csv
├── owid-co2-data-south-korea.csv
└── README.md
```

---

## 💡 How to Run Locally

```r
shiny::runApp("app.R")
```

---

Made with 💚 by [Juhee](https://github.com/Juhee091)  
Dongduk Women's University – Data Science Major (2025)

