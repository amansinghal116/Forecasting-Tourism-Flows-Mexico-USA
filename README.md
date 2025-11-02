🌍 Forecasting Tourism Flows: Predictive Analytics 2025 (Mexico–USA)
📖 Project Overview

This project focuses on forecasting short-term U.S. tourist arrivals to Mexico using real-world tourism and macroeconomic data.
The goal is to help tourism stakeholders anticipate seasonal demand, optimize resource allocation, and support data-driven planning in the tourism sector.

The analysis compares multiple forecasting models to determine the most accurate, interpretable, and practical approach for short-term tourism flow prediction.

🧩 Data Sources

dataTour.Rdata – Contains quarterly tourism flows between 20 destination countries and their respective origin countries.

Each destination includes 5 origin countries, a Total column, and a Difference column (tourists not from the 5 listed origins).

IMFdata.Rdata – Includes macroeconomic indicators for 46 countries such as GDP growth and purchasing power parity (PPP), which support regression-based forecasting.

⚙️ Methodology

A series of forecasting models were developed and evaluated to capture the behavior of quarterly tourism flows:

Seasonal Naïve Model – Baseline model capturing recurring seasonal patterns.

Exponential Smoothing (ETS) – Captures level, trend, and seasonality (notably ETS(A,Ad,A)).

Autoregressive Lag Model (AR) – Models short-term temporal dependencies.

Lag Model with Seasonal Dummies – Accounts for quarter-specific effects.

Macroeconomic Regression Model – Incorporates indicators such as U.S. GDP growth and Mexico’s PPP to connect tourism with economic factors.

Evaluation Metrics:

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

Validation was conducted using data up to 2018, with an out-of-sample test period (2019) to assess generalization and reliability.

📊 Key Findings

The Seasonal Naïve model achieved the lowest RMSE and MAE, making it the most reliable and practical model for short-term forecasts.

The ETS model effectively captured trends but showed mild overfitting on the test period.

Lag models provided useful insights into quarterly dependencies but underperformed on unseen data.

The Macroeconomic regression model improved interpretability but exhibited higher forecast error.

✅ Conclusion:
Tourism flows between the U.S. and Mexico exhibit a stable and recurring seasonal pattern.
The Seasonal Naïve approach offers the most robust, interpretable, and operationally useful short-term forecast.
ETS and regression models can supplement long-term strategic and scenario analyses.

🧠 Tools & Technologies

R Programming Language

Time Series Forecasting Techniques (ETS, AR, Regression)

Statistical Evaluation Metrics: RMSE, MAE

Data Visualization & Diagnostics using R packages for time series analysis

📈 Practical Applications

This forecasting framework supports:

Anticipating and managing seasonal tourism demand

Resource planning (staffing, marketing, infrastructure)

Integrating economic indicators into strategic decision-making

Enhancing responsiveness to market changes and seasonal patterns

👨‍💻 Author

Aman Singhal
🎓 Master’s Student in Data Science
📁 Project Title: Predictive Analytics 2025 – Tourism Forecasting (Mexico–USA)
