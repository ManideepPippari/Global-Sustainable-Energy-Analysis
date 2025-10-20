# 🌍 Global Sustainable Energy Analysis and 2030 Forecast

## Project Overview

This project analyzes **global energy consumption**, **renewable energy adoption**, and **CO₂ emissions** using the Our World in Data (OWID) dataset.

The core goals are:
1.  Visualize global and country-specific energy trends (2000s - present).
2.  Analyze the correlation between economic indicators (GDP) and energy metrics (CO₂, Renewables).
3.  Employ machine learning models (Linear, Polynomial, and Random Forest Regression) to **predict the global renewable energy share for the year 2030**.

***

## 🔍 Key Insights (Complete after running the script)

* **Model Performance:** The **Random Forest Regressor** achieved the highest accuracy ($R^2$ Score: **[Insert RF R² Score Here]**), making it the most reliable predictor.
* **2030 Forecast:** Based on the Random Forest model, the global renewable share in total final energy consumption is predicted to be approximately **[Insert RF Prediction Here]**% by 2030.
* **Visualizations:** The project includes interactive choropleth maps (in the `visualizations` folder) highlighting disparities in renewable energy capacity and CO₂ emissions across nations.

***

## 🚀 Getting Started

### Prerequisites

You need **Python 3.x** and the following libraries installed.

To set up your environment, use the provided `requirements.txt` file:

```bash
pip install -r requirements.txt