# eda-global-air-quality
EDA on Air Quality dataset using Python (college mini-project)
# 🌍 Global Air Quality Analysis (EDA)

## 📌 Project Description
This project performs Exploratory Data Analysis (EDA) on a global air quality dataset to identify key pollutants affecting air quality and understand how environmental factors influence pollution levels.

---

## 🎯 Objective
- Identify major pollutants contributing to poor air quality  
- Analyze impact of temperature, humidity, and wind speed  
- Provide insights for better environmental decision-making  

---

## 🛠️ Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📊 Dataset Details
- Total Records: 3660  
- Features: 13  
- Includes:
  - AQI (Air Quality Index)
  - Pollutants: PM2.5, PM10, NO2, SO2, CO, O3
  - Weather: Temperature, Humidity, Wind Speed  

📌 Dataset Source: Kaggle (add link here)

---

## 📈 Analysis Performed
- Data inspection using head(), tail(), info(), describe()  
- Checked missing values  
- Data visualization:
  - Histogram (PM2.5)
  - Countplot (Wind Speed)
  - Scatter Plot (Temperature vs Humidity)
  - Boxplot (City vs AQI)
  - Pairplot  

---

## 🔍 Key Insights
- PM2.5 and PM10 are major contributors to poor air quality  
- AQI varies significantly across cities  
- Weather conditions influence pollution levels  
- Wind speed affects pollutant dispersion  

---

## ▶️ How to Run

1. Download the repository  
2. Open `.ipynb` file in Jupyter Notebook  
3. Make sure dataset is in same folder  
4. Run all cells  

---

## ⚠️ Important Note
Update dataset path in code:
```python
df = pd.read_csv("data.csv")
