# Weather Classification & Prediction Project

## 📝 Project Overview
This project focuses on classifying and predicting weather types (Rainy, Cloudy, Sunny, Snowy) based on various environmental and atmospheric features. The workflow covers the complete Machine Learning pipeline, including data preprocessing, exploratory data analysis (EDA), visualization, and modeling.

## 📁 Dataset Details
The dataset used: `weather_classification_data.csv`  
Total Records: 13,200  

### Key Features:
- **Temperature (°C):** Range from -25.0 to 109.0  
- **Humidity (%):** Air moisture percentage  
- **Wind Speed (km/h):** Speed of wind in the area  
- **Precipitation (%):** Chance of rainfall or snow  
- **Atmospheric Pressure (hPa):** Air pressure readings  
- **UV Index:** Ultraviolet radiation levels  
- **Visibility (km):** Visual range  
- **Categorical Features:** Cloud Cover, Season (Winter, Spring, Autumn, Summer), Location (Inland, Mountain, Coastal)  

### Target Variable:
- **Weather Type:** Rainy, Cloudy, Sunny, Snowy

## 🛠️ Project Workflow

### 1. Data Manipulation & Cleaning
- **Library Used:** `pandas` for data manipulation  
- **Inspecting Data:** `.head()`, `.describe()`, `.info()`  
- **Feature Selection:** Column & row selection using `.iloc`  
- **Handling Missing Values:** Dataset verified to have **0 missing values** across all features  

### 2. Exploratory Data Analysis (EDA)
- Calculated statistical measures (Mean, Max, Min) for temperature and other features  
- Seasonal analysis revealed **Winter** as the most frequent season (5,610 entries)  

### 3. Data Visualization
- **Library Used:** `matplotlib.pyplot`  
- **Techniques:** Histograms and plots to visualize the relationship between temperature, seasons, and other atmospheric variables  

## 🚀 Getting Started
### Prerequisites
To run this project locally, ensure you have the following Python libraries installed:

## Results & Insights

- The dataset shows a wide range of temperatures (-25°C to 109°C), indicating diverse environmental conditions
- Data preprocessing ensured zero null values and proper feature selection
- Visualizations helped identify patterns in weather conditions across seasons and locations

## 👤 Author

Hafiz Muhammad Faizan
GitHub: https://github.com/thehmfpk
Portfolio: www.hafizmuhammadfaizan.site
