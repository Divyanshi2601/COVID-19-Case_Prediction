# COVID-19-Case_Prediction
#  COVID-19 Case Prediction

##  Project Overview

This project aims to *forecast future COVID-19 cases* using historical time-series data from the *Johns Hopkins University* dataset. By applying regression techniques like *Linear Regression* and *Polynomial Regression*, the model predicts upcoming case trends and visualizes them for better understanding.

##  Objective

> *Create a time-series prediction model to forecast future COVID-19 cases using historical data. Apply regression techniques and visualize trends.*

---

##  Dataset

- *Source*: [Kaggle - COVID-19 Data from Johns Hopkins University](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university)
- *Format*: Multiple CSV files for confirmed cases, deaths, recoveries across regions.
- *Structure*:
  - Columns include: Province/State, Country/Region, Lat, Long, followed by date-wise case counts.
  
---

##  Techniques Used

- 📌 Data Preprocessing
- 📈 Linear Regression
- 🧮 Polynomial Regression (Degree = 4)
- 🔀 Train-Test Split (80/20)
- 📉 Evaluation Metrics: MSE, R²
- 📅 30-Day Future Forecasting
- 📊 Visualization using Matplotlib

---

##  Project Structure

```bash
.
├── covid_data/               # Folder containing extracted CSVs
├── covid_forecasting.ipynb   # Main Jupyter notebook (Colab-compatible)
├── README.md                 # Project documentation
└── requirements.txt          # Python package dependencies


