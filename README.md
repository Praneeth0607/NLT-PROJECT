# Dynamic Night-Time Light-Based Human Activity Change Detection

> Turning Night Lights into Insights Using Satellite Data and Geospatial Intelligence

---

## 📌 Overview

This project presents a dynamic framework for detecting changes in human activity using time-series night-time satellite imagery. The system analyzes VIIRS Day/Night Band (DNB) data to identify persistent increases or decreases in illumination patterns associated with urban growth, infrastructure development, economic activity, and regional decline.

Unlike traditional fixed-threshold methods, the proposed approach uses regression-based trend modeling, residual anomaly detection, dynamic thresholding, persistence analysis, and spatial coherence filtering to improve reliability and reduce false detections.

The implementation is developed using the Google Earth Engine (GEE) platform for large-scale geospatial processing and visualization.

---

## 🚀 Features

- Time-series analysis of VIIRS night-time light data
- Regression-based trend modeling
- Expected brightness prediction
- Residual anomaly detection
- Dynamic thresholding using standard deviation
- Persistence analysis for reliable change detection
- Spatial coherence filtering
- Area estimation of significant changes
- Time-series visualization
- Validation using Sentinel-2 imagery

---

## 🛰️ Dataset Used

### VIIRS Night-Time Light Dataset
- Dataset: `NOAA/VIIRS/DNB/MONTHLY_V1/VCMSLCFG`
- Band Used: `avg_rad`
- Platform: Google Earth Engine

### Validation Dataset
- Dataset: `COPERNICUS/S2_SR`
- Purpose: Visual validation of detected changes

---

## 📍 Study Area

The Region of Interest (ROI) is centered around:

- **Location:** Greater Noida, India
- **Latitude:** 28.4744° N
- **Longitude:** 77.5040° E
- **Buffer Radius:** 12 km

The selected study area enables analysis of rapid urbanization and infrastructure development patterns.

---

## ⚙️ Methodology

The proposed system follows the workflow below:

1. Region of Interest (ROI) Selection  
2. Data Collection and Preprocessing  
3. Time Encoding and Trend Modeling  
4. Expected Brightness Prediction  
5. Residual (Anomaly) Calculation  
6. Dynamic Thresholding  
7. Persistence Analysis  
8. Significant Change Detection  
9. Spatial Coherence Filtering  
10. Time-Series Analysis  
11. Validation Using Sentinel-2 Imagery  

---

## 📊 Results

The system was successfully implemented and evaluated using time-series VIIRS night-time light data.

### Key Outcomes

- Total satellite images processed: **147**
- Historical images used for trend modeling: **72**
- Prediction year images analyzed: **12**
- Persistent increase area detected: **53.30 sq. km**

### Observations

- Significant increase in brightness after 2022
- Persistent illumination growth observed in urban regions
- Results indicate infrastructure expansion and increased human activity
- Spatial filtering improved reliability by removing isolated noise

Validation using Sentinel-2 imagery confirmed that detected regions correspond to actual urban development.

---

## 🧠 Technologies Used

- Google Earth Engine (GEE)
- JavaScript
- Remote Sensing
- Time-Series Analysis
- Spatial Analysis
- Machine Learning Concepts
- Satellite Image Processing

---


