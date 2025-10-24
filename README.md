# Exploratory-Analysis-of-Global-Earthquake-Tsunami-Events-2001-2022-
# 🌋 Earthquake and Tsunami Analysis
# 📖 Project Overview

This project analyzes global earthquake data to identify patterns, trends, and relationships between seismic features and tsunami occurrences.
The goal is to understand how magnitude, depth, location, and time influence tsunami generation and to highlight key thresholds that may indicate increased tsunami potential.

## 📊 Dataset Features
Feature	Description
magnitude	Magnitude of the earthquake (Richter scale)
cdi, mmi, sig, nst, dmin, gap	Seismological parameters (intensity, significance, etc.)
depth	Depth of earthquake focus (in kilometers)
latitude, longitude	Geographic coordinates of the earthquake
Year, Month	Temporal information
tsunami	Binary indicator (1 = tsunami event, 0 = non-tsunami)
## 🧠 Objectives

Analyze the frequency and magnitude of earthquakes over time.

Study the distribution of earthquake magnitudes and depths.

Compare seismic characteristics between tsunami and non-tsunami events.

Identify regions or clusters with higher tsunami concentrations.

Derive insights and thresholds related to tsunami potential.

## 📈 Visual Analyses
1. Earthquake Trends Over Time

Line plots show the frequency and average magnitude of earthquakes per year.

Key observation: Overall earthquake frequency fluctuates yearly, with occasional spikes in both count and magnitude.

2. Magnitude and Depth Distribution

Histograms and KDE plots show most earthquakes occur between 4.0–6.5 magnitude and 10–100 km depth.

Depth distribution is right-skewed — most quakes are shallow to intermediate.

3. Tsunami vs Non-Tsunami Events

Boxplots reveal that tsunami events have:

Higher magnitudes (≥6.5)

Shallower depths (≤50 km)

Bar charts and histograms confirm these trends statistically and visually.

4. Spatial Clustering of Tsunami Events

Scatter plots (Latitude vs Longitude) and Hexbin/KDE density plots highlight regions with dense tsunami activity — notably around the Pacific Ring of Fire, Japan Trench, and Indonesia.

5. Seasonal Patterns

Monthly analysis shows no strong seasonal correlation, but activity peaks in specific months may reflect regional tectonic behavior.

## 🧩 Key Insights and Observations
A. Seismic Differences

Tsunami-triggering earthquakes are stronger and shallower.

Non-tsunami quakes occur more frequently and at all depths.

B. Tsunami Indicators
Indicator	Tsunami-Prone Range	Explanation
Magnitude (Mw)	≥6.5	Higher energy release displaces ocean water
Depth (km)	≤50	Shallow focus transmits more energy to surface
Fault Type	Thrust/Subduction	Vertical seabed displacement most effective
Region	Coastal/Subduction Zones	e.g., Japan, Indonesia, Chile, Alaska
C. Conclusion

The combination of high magnitude + shallow depth + subduction zone location significantly increases tsunami risk.

These findings can guide early warning systems and hazard mitigation planning.

## 🧰 Tools & Libraries Used

Python 3.x

Pandas – data processing

Matplotlib & Seaborn – visualization

NumPy – numerical computation

