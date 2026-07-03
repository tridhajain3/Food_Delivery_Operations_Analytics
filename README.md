# 🚚 Food Delivery Operations Analytics & Delivery Time Prediction System

An end-to-end Data Analytics and Machine Learning project that analyzes food delivery operations and predicts delivery time using interactive business intelligence dashboards and predictive modeling.

## 🌐 Live Dashboard

🔗 **Streamlit Application:** https://fooddeliveryoperationsanalytics-e3ec6j3zwappuqzpesghdwn.streamlit.app/

## 📂 GitHub Repository

🔗 **Repository:** https://github.com/tridhajain3/Food_Delivery_Operations_Analytics

---

# 📌 Project Overview

This project focuses on analyzing food delivery operations data to extract business insights, evaluate operational performance, and predict delivery times using machine learning algorithms.

The system combines:

* Data Validation & Preprocessing
* Exploratory Data Analysis (EDA)
* Business Intelligence Dashboard
* Geographic Delivery Analytics
* Machine Learning Prediction
* Interactive Visualization

The dashboard enables users to analyze delivery operations, rider performance, geographical delivery distribution, and predict estimated delivery times.

---

# 🎯 Business Problem Statement

Food delivery companies need to:

* Reduce delivery delays
* Improve operational efficiency
* Optimize delivery resources
* Understand rider performance
* Analyze delivery patterns geographically
* Predict delivery completion times accurately

This project provides a data-driven solution to support operational decision-making.

---

# 📊 Dataset Information

The dataset contains approximately **45,000+ food delivery records** with features including:

* Delivery Person ID
* Delivery Person Age
* Delivery Person Ratings
* Restaurant Latitude/Longitude
* Customer Latitude/Longitude
* Delivery Distance
* Delivery Type
* Vehicle Type
* Rider Experience
* Delivery Ratings
* Delivery Time

Dataset size:

* **Rows:** 45,162
* **Columns:** 15

---

# 🛠 Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Plotly
* Streamlit

### Machine Learning

* Scikit-Learn
* Random Forest Regressor

### Model Persistence

* Joblib

---

# 📈 Dashboard Features

## Executive Overview

* Total Deliveries
* Average Delivery Time
* Average Delivery Distance
* Average Rider Rating
* KPI Cards

---

## Operations Analytics

* Delivery Time Distribution
* Vehicle Performance Analysis
* Order Type Analysis
* Rider Performance Analytics
* Distance Category Analysis

---

## Geographic Intelligence

* Restaurant Location Distribution
* Delivery Destination Distribution
* Geographic Delivery Heatmaps
* Delivery Density Visualization

---

## Delivery Time Prediction

Users can predict delivery time based on:

* Delivery Distance
* Rider Experience
* Rider Rating
* Vehicle Type
* Order Type

The prediction model provides estimated delivery duration in minutes.

---

# 🤖 Machine Learning Model

The project implements a **Random Forest Regressor** for delivery time prediction.

### Model Workflow

1. Data Cleaning
2. Feature Engineering
3. Feature Selection
4. Train-Test Split
5. Model Training
6. Prediction
7. Evaluation

---

# 📐 Mathematical Concepts & Algorithms Used

## Distance Calculation

Euclidean Distance:

d = √[(x₂ − x₁)² + (y₂ − y₁)²]

Used for calculating delivery distance between restaurant and customer locations.

---

## Statistical Analysis

The project utilizes:

* Mean
* Median
* Standard Deviation
* Variance
* Distribution Analysis
* Frequency Analysis

---

## Machine Learning Algorithm

### Random Forest Regression

Random Forest works by:

* Creating multiple decision trees
* Training each tree on random samples
* Aggregating predictions from all trees

Final prediction:

Prediction = Average(Tree₁ + Tree₂ + ... + Treeₙ)

Benefits:

* Handles nonlinear relationships
* Reduces overfitting
* Provides robust predictions
* High accuracy

---

# 📊 Key Insights Generated

* Delivery distance significantly impacts delivery time.
* Rider experience improves delivery efficiency.
* Vehicle type affects operational performance.
* Delivery ratings correlate with delivery duration.
* Geographic delivery clusters reveal operational hotspots.

---

# 📁 Project Structure

```bash
Food_Delivery_Operations_Analytics/

├── dashboard.py
├── dashboard_backup.py
├── requirements.txt
├── README.md
├── models/
│   └── rf_model.pkl
│
├── cleaned_data/
│   └── food_delivery_cleaned.csv
│
├── outputs/
│
└── reports/
```

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/tridhajain3/Food_Delivery_Operations_Analytics.git
```

Move into the project folder:

```bash
cd Food_Delivery_Operations_Analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run dashboard.py
```

---

# 🌟 Project Highlights

✅ Interactive Business Intelligence Dashboard

✅ Machine Learning Delivery Time Prediction

✅ Geographic Delivery Analytics

✅ Operational Performance Analysis

✅ Interactive Plotly Visualizations

✅ Streamlit Cloud Deployment

✅ End-to-End Data Analytics Workflow

---

# 👩‍💻 Author

**Tridha Jain**

* Data Analytics Enthusiast
* Business Analytics & Consulting Aspirant
* Python | Data Analytics | Machine Learning | Business Intelligence

---

# 🔗 Project Links

### Live Dashboard

https://fooddeliveryoperationsanalytics-e3ec6j3zwappuqzpesghdwn.streamlit.app/

### GitHub Repository

https://github.com/tridhajain3/Food_Delivery_Operations_Analytics
