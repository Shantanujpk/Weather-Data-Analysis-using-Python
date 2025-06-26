# Weather Data Analysis using Python

This project performs Exploratory Data Analysis (EDA) on a weather dataset using Python and Pandas. The objective is to uncover patterns, understand weather conditions, and perform conditional filtering for data-driven insights.

## 📌 Project Description

This notebook-based project analyzes a structured weather dataset to answer various exploratory questions using Python. The dataset includes metrics like temperature, humidity, visibility, weather conditions, and more. The goal is to gain insights into how weather behaves under different conditions and support further analysis or prediction tasks.

## 📊 Key Features

- Grouping weather data by conditions
- Filtering based on specific weather attributes (e.g., visibility > 40 km)
- Identifying unique weather events
- Understanding statistical patterns (mean, max, min) across weather categories

## 🔧 Technologies Used

- Python 🐍
- Pandas
- Jupyter Notebook

## 📁 Project Structure
weather-data-eda/
│
├── Weather Analysis.ipynb # Jupyter Notebook with full analysis
├── README.md # Project overview and setup instructions
└── data/
└── weather.csv # (Optional) Sample dataset if uploaded

## ✅ What I Did

- Imported and cleaned weather data using Pandas
- Performed conditional filtering to answer logical questions
- Handled errors like TypeErrors and ambiguous conditions during filtering
- Grouped data by `Weather Conditions` to compute statistical summaries
- Applied `select_dtypes()` and `numeric_only=True` to fix aggregation issues

## 🎯 Results

- Identified visibility outliers and correlations with weather conditions
- Cleaned dataset ready for deeper statistical modeling
- Clear understanding of weather metrics under different scenarios

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/shantanujpk/Weather-Data-Analysis-using-Python.git
   cd Weather-Data-Analysis-using-Python


pip install pandas jupyter
