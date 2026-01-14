# London Bike Rides Analysis – Data Preparation & Interactive Dashboard

## Overview
This project combines Python-based data preparation with interactive Tableau visualization to analyze
London bike ride patterns across time, weather conditions, and hourly usage. The goal is to transform
raw data into an analysis-ready dataset and deliver intuitive dashboards for exploratory insights.

---

## Project Components
- **Python (Data Preparation & Transformation)**
- **Tableau (Interactive Dashboard & Visual Analytics)**

---

## Data Preparation (Python)
Using Python, the raw dataset was cleaned and transformed to support visualization and analysis:
- Downloaded and extracted the London Bike Sharing dataset from Kaggle
- Cleaned and standardized column names for readability
- Converted and normalized weather-related variables (temperature, humidity, wind speed)
- Mapped numeric season codes to human-readable labels
- Exported the final, cleaned dataset to Excel for BI and dashboard use

---

## Dashboard & Visualization (Tableau)
An interactive Tableau dashboard was built to explore ride behavior across time and environmental factors:
- Total rides and moving average trends across selected time periods
- Temperature vs. wind speed heatmap to analyze weather impact on ridership
- Time-based filters to dynamically explore trends between May and December
- **Hover-based visualization using Viz in Tooltip**, displaying:
  - Weather condition breakdown
  - Hourly ride distribution  
 

---

## Key Insights
- Bike ridership increases significantly during warmer months and moderate weather conditions
- Moving averages reveal clear seasonal peaks and declines in usage
- Weather and time-of-day strongly influence ride volume
- Hover-based tooltips improve interpretability by surfacing contextual details without cluttering the dashboard

---

## Dashboard Preview
![London Bike Dashboard – without Tooltip View](London_bike.png)

🔗 **Live Interactive Dashboard (Tableau Public):**  
https://public.tableau.com/app/profile/bharati.kalambe/viz/LondonBikesDashboard_17684319360600/Dashboard1?publish=yes

![London Bike Dashboard – ](London_bike_tooltip.png)

---

## Tools & Skills
- **Python**: Pandas, NumPy, data cleaning & transformation
- **Data Preparation**: Feature engineering, normalization, categorical mapping
- **Tableau**: Interactive dashboards, filters, KPIs, Viz in Tooltip
- **Analytics**: Time-series analysis, weather impact analysis
- **Data Storytelling**: Translating data into intuitive business visuals

---

## Output
- Cleaned, analysis-ready dataset (Excel)
- Interactive Tableau dashboard with hover-based insights

---

## Future Enhancements
- Integrate predictive models for demand forecasting
- Add real-time weather feeds
- Extend analysis with weekday vs. weekend behavioral patterns

