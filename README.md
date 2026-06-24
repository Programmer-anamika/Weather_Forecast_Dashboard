Weather & Air Quality Analytics Dashboard (Power BI) 🌍📊

An advanced, custom-themed Power BI dashboard that aggregates, models, and visualizes real-time meteorological conditions, forecasting trends, and critical air quality indicators. This project showcases data transformation (Power Query), DAX engineering, and user-centric.


📸 Dashboard Preview
**Note:** The interface features a custom dark/warm-toned aesthetic designed to optimize readability across diverse environmental metrics.

[Power BI Dashboard Layout]

**Show what the dashboard look like**: https://github.com/Programmer-anamika/Weather_Forecast_Dashboard/blob/main/Weather_Dashboard.png  

 🧠 Project Architecture & Features

As demonstrated in `Weather_Dashboard_2.jpg`, this report utilizes complex data relationships to surface deep environmental insights:

**KPI Multi-Cards:** Streamlined reporting of core real-time metrics including Temperature (°C), Humidity, Wind Speed (Kph), Visibility, Barometric Pressure, and UV Index.
**Dynamic Predictive Forecasting:** A customized trend visualization tracking multi-day forecasted temperature variations down to granular decimal points (ranging from $31.83^\circ\text{C}$ to $30.56^\circ\text{C}$).
**Comprehensive Air Quality Index (AQI):** A centralized conditional-formatting radial gauge tracking the primary PM10 metric alongside detailed breakouts for specific atmospheric pollutants ($\text{O}_3$, $\text{SO}_2$, $\text{PM}_{2.5}$, $\text{CO}$, $\text{NO}_2$).
**Cross-Filtering & Localization:** Built-in support for switching between geographic regional data (such as Bangalore, Assam, and Gujarat) with full cross-filtering across all report visuals.
**Probability Tracking Matrix:** A structured visualization breaking down the "Chance of Rain" by specific calendar days.


🛠️ Tech Stack & Skills Demonstrated

**Tool:** Power BI Desktop
**Data Transformation:** Power Query (M Language) for ETL, data cleaning, and structuring unpivoted weather metrics.
**Data Modeling:** Star Schema design mapping date dimensions, regional attributes, and factual weather readings.
**DAX (Data Analysis Expressions):** Used for calculating rolling averages for weather forecasting, conditional formatting rules, and localized string concatenations.
**UI/UX Design:** Custom grid alignment, glassmorphic card overlays, and conditional KPI status coloring (e.g., green indicators for safe AQI parameters).

