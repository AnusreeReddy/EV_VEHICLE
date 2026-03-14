# 🚗 EV Adoption Forecasting App

An interactive web app built with **Python** and **Streamlit** to forecast Electric Vehicle (EV) adoption trends across selected U.S. counties.

---

# 📌 Features

- Predicts future EV counts using **Random Forest Regressor** trained on historical data.
- Users can select and compare up to **three counties** simultaneously.
- Handles missing or insufficient data dynamically for smooth user experience.
- Visualizes both **historical and forecasted trends** using clear comparative line charts.

---

# 📊 Methodology

## Data Preprocessing

- Cleaned and organized historical EV data.
- Managed missing values and structured the dataset for modeling.

## Feature Engineering

Generated statistical features to capture temporal patterns:

- Lag features
- Rolling means
- Percent changes
- Growth slope indicators

## Model Training

- Trained a **Random Forest Regressor** on processed data.
- The model learns patterns in EV adoption growth across counties.

## Forecast Generation

- Used the trained model to predict **future EV adoption trends**.

---

# 📈 Visualization

The Streamlit interface allows users to:

- Select and compare **multiple counties**
- View **historical EV growth**
- Display **future forecasted trends**
- Compare adoption patterns using **interactive line charts**

---

# 🛠 Tools & Technologies

## Programming
- Python

## Libraries
- Pandas  
- Scikit-learn  
- Streamlit  
- Matplotlib  

## Machine Learning
- Random Forest Regressor

## Data Processing
- Lag features  
- Rolling statistics  
- Trend-based transformations

---

# 🔗 Try It Yourself

Clone this repository and run the Streamlit application:

```bash
streamlit run app.py
