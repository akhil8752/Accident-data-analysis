# 🚧 UK Road Accident Dashboard (Tableau Project)

This Tableau dashboard project visualizes road accident data from the UK to uncover insights about accident severity, weather conditions, road types, and other contributing factors. The dataset used is based on real accident records from regions such as Kensington and Chelsea.

## 📊 Dataset Overview

Each row in the dataset represents a single accident case and includes details like:

- `Accident_Severity`: Level of accident (e.g., Serious, Slight, Fatal)
- `Accident_Date`: Date of the accident (e.g., 05-06-2019)
- `Latitude` & `Longitude`: Geographic location of the accident
- `Light_Conditions`: Lighting condition during the accident (e.g., Darkness - lights lit)
- `District_Area`: Local district where the accident occurred
- `Number_of_Casualties`: Total number of people injured or killed
- `Number_of_Vehicles`: Number of vehicles involved in the accident
- `Road_Surface_Conditions`: Road condition at the time (e.g., Dry, Wet)
- `Road_Type`: Type of road (e.g., Single carriageway)
- `Urban_or_Rural_Area`: Whether the area is urban or rural
- `Weather_Conditions`: Weather at the time (e.g., Fine no high winds)
- `Vehicle_Type`: Type of vehicle involved (e.g., Car, Motorcycle, etc.)

## 🔍 Objective

The main goals of this project are:
- To identify patterns in accident severity across time and location.
- To evaluate how environmental and road conditions affect accident rates.
- To provide an interactive and user-friendly dashboard for quick analysis.

## 🧩 Key Visualizations

- **Severity Distribution**: Pie chart or bar chart showing the frequency of each accident severity.
- **Time Analysis**: Line chart showing accident trends over time.
- **Geographic Map**: Map plot showing accident locations using latitude and longitude.
- **Filter Panels**: Dynamic filters to slice data by vehicle type, weather, road surface, etc.
- **Casualty vs Vehicles**: Scatter plot or KPI cards comparing number of vehicles involved to number of casualties.

## 📌 Tools Used

- **Tableau** – For creating interactive dashboards
- **Excel/CSV** – Initial data cleaning and preparation
- **Markdown** – For documentation

## 📁 Project Structure

```plaintext
📦 UK_Accident_Analysis
├── data/
│   └── accident_data.csv
├── dashboard/
│   └── accident_dashboard.twbx
└── README.md

