# Hyper-AQI-Dashboard
AI-powered Hyper-Local AQI dashboard that combines satellite, sensor, and weather data to detect pollution sources, forecast air quality, and provide targeted health advisories and government insights.

## Problem
Current systems provide only city-level AQI, hiding dangerous pollution variations across neighborhoods.

## Solution
An AI-powered dashboard that combines satellite data, sensor data, weather APIs, and traffic information to detect pollution sources and forecast air quality.

## Key Features
- Hyper-local AQI mapping using geo-grids
- Pollution source detection (construction, traffic, biomass burning)
- Machine learning based pollution forecasting
- Health advisories for sensitive groups
- Decision support dashboard for government agencies

## Technology Stack
- Python
- GeoPandas
- PostGIS
- FastAPI
- Mapbox GL JS
- Chart.js
- XGBoost
- Isolation Forest

## System Architecture
Data is collected from APIs and satellite sources, processed using geospatial tools, analyzed using machine learning models, and visualized through an interactive dashboard.

## Repository Structure
Hyper-AQI-Dashboard
│
├── data
├── backend
├── ml_models
├── geospatial
├── frontend
├── alerts
└── docs


## Impact
- Provides localized pollution monitoring
- Helps authorities take faster action
- Protects vulnerable populations through targeted alerts

## Team
