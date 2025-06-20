# 🍷 Iowa Alcohol Sales Analysis
This project investigates liquor sales trends in Iowa and how they relate to broader societal, demographic, and policy factors. The analysis combines historical sales data, census information, geospatial datasets, and machine learning techniques to explore how alcohol consumption reflects Iowa’s evolving population and cultural landscape.

## 🧠 Objective
To analyze liquor sales trends across Iowa and understand their relationship with:

- Population size and urbanization

- Income and socioeconomic factors

- Policy and cultural shifts

- Predict future trends in alcohol sales

## 📁 Datasets
Iowa Alcohol Sales (29.9M records, sample of 500k used)

US Census Data (population & income)

Iowa Geospatial Data (county-level mapping and outlet density)

## 📊 Methods & Techniques
### 🔍 Exploratory Data Analysis
Cleaned and transformed the data

Engineered features like average income and population

Visualized sales, volume, and population distributions

### 🗺️ Geospatial Visualization
Mapped alcohol outlet density by county

Tracked population and income changes over time

Compared urban vs. rural consumption patterns

### 📈 Multivariable & Correlation Analysis
Alcohol Sales per Capita vs:

- Population → Correlation: 0.46

- Income → Correlation: 0.05

### 🧠 Supervised Learning
Regression Models to predict total sales per county:

- Linear Regression: R² = 0.819

- Random Forest Regression: R² = 0.817

Key Predictive Features: Population, vendor count, product variety, urbanization

### ⏳ Time Series Forecasting
Built a SARIMA model to forecast liquor sales

Identified seasonal spikes (e.g., holidays)

Predicted future decline in sales due to rising health-conscious behaviors

### 🤖 Unsupervised Learning
PCA for dimensionality reduction

K-Means Clustering to segment counties

Revealed distinct markets for high-volume vs. high-end liquor

Urban areas dominated premium sales

## 📌 Key Findings
### Finding	Insight
Urbanization	Urban counties (e.g., Polk, Linn) show higher alcohol sales
Income	Weak correlation with sales; social factors more impactful
Seasonality	Sales spike during holidays; forecast shows future decline
Clusters	Urban counties drive high-end sales; volume varies by region

## ✅ Conclusion
Alcohol consumption in Iowa is shaped more by social and urban factors than income.

Public health policy should focus on regulating outlet density in cities.

Forecasting models suggest a cultural shift toward reduced alcohol consumption.
