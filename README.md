#  Air Quality Analysis — Indian Cities

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/air-quality-india/blob/main/Air_Quality_Analysis_Indian_Cities.ipynb)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![License](https://img.shields.io/badge/License-MIT-green)

> Analyzing **PM2.5 pollution trends** across **Chennai, Delhi & Mumbai** — with seasonal patterns, Diwali spikes, and year-over-year comparisons (2019–2024).

---

##  Project Overview

Air pollution is one of India's most critical public health challenges. This project analyzes **PM2.5 particulate matter** across three major Indian cities using real data from the **OpenAQ API** and CPCB-calibrated historical profiles.

### Key Questions Explored:
- Which city has the worst air quality and when?
- How do seasons (Winter / Monsoon / Summer) affect pollution levels?
- How much does PM2.5 spike during **Diwali**?
- Has air quality improved year-over-year?
- What was the COVID-19 lockdown effect on AQI?

---

##  Visualizations

| Chart | Description |
|-------|-------------|
| `trend_annual.png` | Monthly PM2.5 trend with Diwali markers |
| `seasonal_analysis.png` | Seasonal avg by city |
| `diwali_spike.png` | PM2.5 ±7 days around Diwali |
| `monthly_heatmap.png` | Year × Month heatmap |
| `aqi_distribution.png` | AQI category pie charts |
| `boxplot_season.png` | Box plot: season × city |
| `yoy_trend.png` | Year-over-year with trend lines |

---

##  Key Findings

- **Delhi** averages **~120 µg/m³** — over **8× the WHO guideline** of 15 µg/m³
- **Diwali spikes** PM2.5 by **~200%** in Delhi, ~75% in Mumbai, ~50% in Chennai
- **Winter (Dec–Jan)** is consistently the worst season across all cities
- **Monsoon season** provides natural air cleansing — lowest PM2.5 across all cities
- COVID-19 lockdown (2020) caused a measurable drop in pollution levels

---

##  Tech Stack

- `pandas` — Data wrangling
- `numpy` — Numerical operations
- `matplotlib` + `seaborn` — Static visualizations
- `plotly` — Interactive charts
- `requests` — OpenAQ API calls

---

##  How to Run

### Option 1: Google Colab (Recommended)
Click the **Open in Colab** badge above.


---

##  Repository Structure

```
air-quality-india/
│
├── Air_Quality_Analysis_Indian_Cities.ipynb  ← Main notebook
├── README.md
├── requirements.txt
├── data/
│   ├── air_quality_india_2019_2024.csv
│   ├── monthly_averages.csv
│   └── summary_statistics.csv
└── images/
    ├── trend_annual.png
    ├── seasonal_analysis.png
    ├── diwali_spike.png
    ├── monthly_heatmap.png
    ├── aqi_distribution.png
    ├── boxplot_season.png
    └── yoy_trend.png
```

---


##  Insights
<img width="1651" height="693" alt="image" src="https://github.com/user-attachments/assets/39da09a4-acdc-4d50-b519-e030757c3dda" />
<img width="694" height="590" alt="image" src="https://github.com/user-attachments/assets/98f2025c-22f5-4635-a235-081275871634" />


---

##  Data Sources

- **[OpenAQ](https://openaq.org/)** — Real-time & historical air quality data (free API)
- **[CPCB](https://cpcb.nic.in/)** — India's Central Pollution Control Board reports
- Historical seasonal profiles calibrated from published research on Indian city AQI patterns

---

##  Future Work

- [ ] Add FB Prophet / LSTM forecasting for next 30 days
- [ ] Expand to Bengaluru, Hyderabad, Kolkata
- [ ] Correlate with NASA MODIS satellite aerosol data
- [ ] Deploy as live Streamlit dashboard
- [ ] Analyze other festivals: Holi, New Year, Chhath Puja

---
