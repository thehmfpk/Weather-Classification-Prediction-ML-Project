Weather Classification & Prediction Project
📝 Project Overview
This project aims to classify and predict weather types (Rainy, Cloudy, Sunny, Snowy) based on various environmental and atmospheric features. The project covers the end-to-end Machine Learning pipeline, including data manipulation, exploratory data analysis (EDA), and data visualization.

📁 Dataset Details
The dataset used is weather_classification_data.csv, which consists of 13,200 records.

Key Features:
Temperature: Range from -25.0°C to 109.0°C.

Humidity: Air moisture percentage.

Wind Speed: Speed of wind in the area.

Precipitation (%): Chance of rainfall/snow.

Atmospheric Pressure: Air pressure readings.

UV Index: Ultraviolet radiation levels.

Visibility (km): Visual range.

Categorical Features: Cloud Cover, Season (Winter, Spring, Autumn, Summer), and Location (Inland, Mountain, Coastal).

Target Variable: Weather Type (Rainy, Cloudy, Sunny, Snowy).

🛠️ Project Workflow
1. Data Manipulation & Cleaning
Library Used: pandas for data reshaping and manipulation.

Inspecting Data: Utilized .head(), .describe(), and .info() to understand the dataset structure.

Feature Selection: Performed column and row selection using .iloc and specific index mapping.

Handling Missing Values: Verified that the dataset contains 0 missing values across all 11 columns.

2. Exploratory Data Analysis (EDA)
Analyzed statistical measures (Mean, Max, Min) for temperature.

Seasonal Analysis: Identified that "Winter" is the most frequent season in the dataset with 5,610 entries.

3. Data Visualization
Library Used: matplotlib.pyplot.

Techniques: Generated histograms to visualize the distribution of seasons against temperature and other atmospheric variables to identify trends.

🚀 Getting Started
Prerequisites
To run the notebook locally, you will need the following Python libraries:


📊 Results & Insights
The dataset shows a wide range of temperatures (-25°C to 109°C), indicating diverse environmental conditions.

The project successfully prepared the data for classification by ensuring zero null values and proper feature scaling/selection.

👤 Author
Hafiz M. Faizan
