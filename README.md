# 📊 Performance Marketing Funnel Analyzer

A **data-driven dashboard and ML project** to analyze and optimize paid digital campaigns across three channels: **Google Ads, Instagram, and YouTube**.

---

## 🚀 Overview

- Simulates and analyzes marketing performance data for Google Ads, Instagram, and YouTube.
- Provides an end-to-end view of campaign efficiency using key KPIs and predictive modeling.
- In-depth performance analysis conducted using **Excel, SQL, and Power BI**.

---

## 📌 Features

- **📈 Interactive Dashboard**
  - Track CTR, CPA, funnel stages, and ROI over time.
  - ![Dashboard Screenshot](https://github.com/user-attachments/assets/13c32223-21fc-4f35-ab79-13324b36f3e4)

- **🤖 ML-Based Purchase Prediction**
  - Predicts conversion volume using impressions, clicks, signups, and spend.
  - Utilizes a Linear Regression model in Python.
  - **Model Performance:**
    - Mean Squared Error (MSE): **711** (predictions deviate by ≈ 26.7 purchases on average)
    - R² Score: **0.7077** (explains 71% of the variation in purchases)

- **📊 Channel Comparison & Optimization**
  - Visual insights to identify top-performing platforms.
  - Optimize ad spend using interactive Power BI dashboards.

---

## 🛠️ Tech Stack

- **SQL** – Data aggregation & KPI calculation
- **Excel** – Exploratory analysis & initial dashboards with graphs and pivot tables
- **Power BI** – Interactive KPI dashboard with filters and trends
- **Python (scikit-learn)** – ML model for purchase prediction
- **Pandas, NumPy, Matplotlib** – Data processing and evaluation

---

## 📂 Files Included

- `ad_campaign_data.csv` – Simulated marketing data (60 days × 3 channels)
- `ads_campaign_dashboard.pbix` – Power BI interactive dashboard
- `ads_campaign_MLmodel.py` – ML model training and evaluation
- `ad_campaign_data_with_predictions.csv` – Dataset with predicted purchases

---

## 📈 Sample KPIs Visualized

- **Click Through Rate (CTR)**
- **Signup & Purchase Rates**
- **Cost Per Acquisition (CPA)**
- **Funnel Drop-off Analysis**
- **Spend vs. ROI per Channel**

---

## 📊 Results

- 📉 Reduced cost per purchase through predictive insights
- 🔍 Identified highest ROI channels using KPI benchmarks
- 📊 Delivered clear visual storylines for campaign effectiveness

---

## 📎 How to Run

1. **Load** `ad_campaign_data.csv` in Power BI or Excel.
2. **Run** `ads_campaign_MLmodel.py` to generate purchase predictions.
3. **Explore** trends by date/channel using slicers and filters in Power BI.

---
