# Traffic Accident Analysis

Exploratory data analysis on traffic accident data to uncover patterns in accident frequency, severity, and contributing factors. The goal is to identify high-risk conditions and provide data-driven safety insights.

## Objective

Road traffic accidents are a major public safety concern. This project uses EDA techniques to answer questions like:
- When and where do accidents happen most?
- Which conditions (weather, road type, time of day) are linked to severe accidents?
- What patterns emerge that could inform traffic safety policy?

## Dataset

The dataset contains records of traffic accidents with features including:
- Date, time, and location of accidents
- Weather conditions and road surface type
- Severity level of the accident
- Number of vehicles and casualties involved

## Analysis Performed

**1. Temporal Analysis**
- Accident frequency by hour of day, day of week, and month
- Identifying peak accident windows (rush hours, weekends)

**2. Severity Analysis**
- Distribution of accident severity across the dataset
- Conditions most associated with fatal or serious accidents

**3. Environmental Factors**
- Impact of weather conditions on accident rates
- Road type and surface condition analysis

**4. Visualizations**
- Heatmaps for time-of-day vs day-of-week accident frequency
- Bar charts and pie charts for categorical breakdowns
- Trend lines for accident patterns over time

## Key Insights

- Accidents peak during morning (8-9 AM) and evening (5-6 PM) rush hours
- Wet road surfaces are linked to disproportionately more severe accidents
- Fridays and Saturdays show elevated accident counts compared to midweek

## Tools & Libraries

- **Python** - Pandas, NumPy
- **Visualization** - Matplotlib, Seaborn
- **Environment** - Jupyter Notebook

## How to Run

```bash
git clone https://github.com/210306105059/Traffic-Accident-Analysis.git
cd Traffic-Accident-Analysis
pip install pandas numpy matplotlib seaborn
jupyter notebook traffic_accident_analysis.ipynb
```

---
*If you find this analysis useful or have suggestions, feel free to open an issue.*
