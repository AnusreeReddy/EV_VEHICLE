🚗 EV Adoption Forecasting App

An interactive web application built using Python and Streamlit to forecast Electric Vehicle (EV) adoption trends across selected U.S. counties using machine learning.

📌 Features

Forecasts future EV adoption trends using a Random Forest Regressor trained on historical EV registration data.

Allows users to select and compare up to three counties simultaneously.

Automatically handles missing or insufficient data to maintain a smooth user experience.

Visualizes historical and predicted EV adoption trends using interactive comparative line charts.

📊 Dataset

Source: U.S. EV Registration Data

Data Type: County-level EV population statistics

Time Range: Historical EV counts across multiple years

The dataset was cleaned and preprocessed before training the forecasting model.

🧠 Methodology

The forecasting pipeline consists of the following steps:

1️⃣ Data Preprocessing

Removed missing or inconsistent entries

Organized EV counts by county and year

2️⃣ Feature Engineering

Generated statistical features to capture temporal patterns:

Lag features

Rolling means

Percentage change

Growth slope indicators

These features help the model understand historical adoption trends.

3️⃣ Model Training

A Random Forest Regressor was trained on the engineered features to learn non-linear patterns in EV adoption trends.

4️⃣ Forecast Generation

The trained model predicts future EV adoption counts based on historical growth patterns.

📈 Visualization

The Streamlit interface allows users to:

Select counties for comparison

Visualize historical EV growth

Display future forecasted adoption trends

Interactive charts make it easier to compare EV adoption across regions.

🛠 Tools & Technologies

Programming: Python

Libraries:

Pandas

Scikit-learn

Matplotlib

Streamlit

Machine Learning Model:

Random Forest Regressor

Feature Engineering Techniques:

Lag features

Rolling statistics

Trend-based transformations

⚙️ Running the Application

Clone the repository and run the Streamlit app:

git clone <repo-link>
cd ev-adoption-forecast
streamlit run app.py

The app will launch in your browser.

🚀 Future Improvements

Incorporate additional models such as ARIMA and LSTM for time-series comparison.

Add hyperparameter tuning to improve prediction accuracy.

Expand dataset coverage to include more geographic regions.
