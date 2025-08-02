# 🚗 EV Adoption Forecasting App

An interactive web app built with **Python** and **Streamlit** to forecast Electric Vehicle (EV) adoption trends across selected U.S. counties.

## 📌 Features

- Predicts future EV counts using **Random Forest Regressor** trained on historical data.
- Users can select and compare up to **three counties** simultaneously.
- Handles missing/insufficient data dynamically for smooth user experience.
- Visualizes both historical and forecasted trends using clear, comparative line charts.

## 📊 Methodology

- Historical EV data preprocessing with lag-based statistical features:
  - Lags, rolling means, percent changes, and growth slopes.
- Trained a Random Forest Regressor on processed data.
- Forecasted future adoption using learned patterns.
- Deployed the model with an interactive frontend via **Streamlit**.

## 🛠 Tools & Technologies

- Python, Pandas, Scikit-learn, Streamlit, Matplotlib
- Machine Learning: Random Forest Regressor
- Data Handling: Lag features, trend-based transformations

## 🔗 Try it Yourself

> Clone this repo and run:
```bash
streamlit run app.py
