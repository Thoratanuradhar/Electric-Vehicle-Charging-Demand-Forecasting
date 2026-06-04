
## Project Overview
The rapid growth of electric vehicles (EVs) has created a need for efficient charging infrastructure and smart energy management.  
This project applies time-series forecasting techniques to predict EV charging demand, helping optimize grid usage, reduce energy wastage, and improve charging station efficiency.

## Abstract
- Historical EV charging data analyzed with **Python** and forecasting models.  
- Features engineered: time-based variables, lag features, rolling averages.  
- Models implemented: **ARIMA** and **Prophet**.  
- Evaluation metrics: **MAE** and **RMSE**.  
- Interactive dashboards built in **Tableau** for visualization.  

## Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)  
- Matplotlib & Seaborn  
- ARIMA & Prophet models  
- Jupyter Notebook / Google Colab  
- Tableau for dashboards  

## Project Workflow
1. Data import & inspection  
2. Timestamp conversion & preprocessing  
3. Feature engineering (hour, day, month, weekend indicators)  
4. Lag variables & rolling mean generation  
5. Exploratory Data Analysis (EDA)  
6. Train-test split  
7. Forecasting with ARIMA & Prophet  
8. Model evaluation (MAE, RMSE)  
9. Dashboard creation for insights  

## Dashboard Preview
<img width="999" height="701" alt="image" src="https://github.com/user-attachments/assets/6e2dfab8-8e99-4ab0-a085-1d4c8b3c15da" />

The EV Charging Demand Forecasting Dashboard provides an interactive view of charging demand patterns and their external drivers. It integrates time, weather, traffic, and forecasting models into a single interface for actionable insights.
1. Heatmap (Hour vs Day): 
Visualizes demand intensity across different hours and days, with color-coded weather conditions (Clear, Cloudy, Rainy). Helps identify peak usage periods.
2. Forecast Chart (Timestamp vs Demand):
Displays predicted demand (Yhat) extending into 2025, generated using ARIMA and Prophet models. Highlights future demand trends.
3.  Weather Condition Bar Chart  
Compares demand under Cloudy, Rainy, and Clear conditions (~100K demand each), showing how weather influences charging behavior.
4.  Traffic vs Demand Chart:  
Plots demand against traffic volume (traffic_num), with demand reaching up to 300K, revealing the impact of traffic flow on charging demand.
5.  Data Guide Panel:
Lists the data source (cleaned_ev_data.csv) and confirms no outlier marks found, ensuring data quality and transparency.

## Results
- ARIMA and Prophet models captured demand patterns effectively.  
- Forecasts support **resource allocation**, **peak-hour management**, and **renewable energy integration**.  
- Visualizations highlight correlations between **weather, traffic, and demand**.  

