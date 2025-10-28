# 🌍 Carbon Emissions Prediction Platform

**Cloud-hosted web application built for Armanino LLP**  
**Tech Stack:** Python · Machine Learning · Flask · AWS · Excel · ARIMA · SARIMAX · Pandas · NumPy · Scikit-Learn

---

## 📘 Overview
- This project predicts and visualizes carbon emissions for organizations using historical data and time-series forecasting models.  
- The platform was developed as part of an academic-industry practicum project to help clients analyze and plan sustainability goals.

---

## ⚙️ Key Features
- Uploads datasets (Excel/CSV) for energy usage and emissions records  
- Cleans and preprocesses data automatically using Pandas  
- Trains and tests ARIMA and SARIMAX models for CO₂ emission forecasting  
- Visualizes trends using Matplotlib and Seaborn  
- Deployed on AWS with Flask web interface for user interaction

---

## 🧠 Machine Learning Models
- **ARIMA:** Captures historical linear patterns and seasonality  
- **SARIMAX:** Incorporates external variables for improved accuracy  
- **Evaluation Metrics:** MAPE, RMSE, and correlation analysis  

---

## 🗂️ Project Structure

carbon-emissions-prediction-platform/

├── data/ # Sample cleaned dataset

├── notebooks/ # Jupyter notebooks for analysis

├── src/ # Flask app and ML scripts

├── static/ # CSS / JS for web interface

├── templates/ # HTML files (Flask views)

└── README.md


---

## 🚀 How to Run Locally
```bash
# Clone repository
git clone https://github.com/Kapil-Jobanputra/carbon-emissions-prediction-platform.git

# Navigate into project
cd carbon-emissions-prediction-platform

# Install dependencies
pip install -r requirements.txt

# Run Flask app
python app.py

🧾 Results & Insights

Achieved accurate multi-year emission forecasting using ARIMA/SARIMAX.

Helped visualize reduction opportunities and energy trends.

Improved model accuracy by integrating cleaned external datasets (temperature, industry data).

👨‍💻 Role & Responsibilities

Designed and developed the end-to-end architecture using Flask and AWS.

Built a forecasting pipeline and model evaluation framework.

Led data collection, cleaning, and transformation stages in Excel and Python.

Coordinated deployment and presentation to Armanino LLP stakeholders.

🧩 Future Enhancements

Integrate API for real-time data updates.

Add user authentication and dashboard analytics.

Containerize using Docker for scalable deploymen.t

⭐ This project demonstrates data analytics, machine learning, and cloud deployment skills for sustainable tech solutions.
