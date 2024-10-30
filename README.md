# Kilimo Riziki Project
**By:**
 Flavine Ezra


---

## Introduction
Kenya's agricultural sector is undergoing transformative changes through agri-tech initiatives led by organizations such as the Kenya Agricultural and Livestock Research Organization (KALRO) and various startups. Their primary focus is on enhancing farming practices, market access, and decision-making processes.

---

## Problem Statement
The agricultural sector in Kenya plays a vital role in the economy, influenced by factors such as population dynamics, agricultural inputs, crop prices, GDP, and climate conditions. Investors require a comprehensive decision-making tool that integrates historical data to provide insights and guide strategic investments.

---

## Objectives
1. **Predictive Analysis (2023-2027):**
   - Population growth rate per county
   - Costs of agricultural inputs (e.g., Fertilizers, Crop chemicals, Fuel and power, Certified Seeds)
   - Retail prices of key crops: Maize, Beans, Millet, Tomatoes, Sorghum, Potatoes, Cabbages, and Bananas
   - Average rainfall and temperature variations
   - GDP of Agricultural Practices, with a focus on Growing of Crops

2. **Risk Criteria and Recommender System:**
   - Establish risk criteria for each crop annually and per county.
   - Implement the KilimoRiziki Decision Hub recommender system across various platforms.

---

## Data Source
The dataset for this project was sourced from [here]().

---

## Methods Applied

### 1. Exploratory Data Analysis (EDA)
We conducted EDA to comprehend patterns, correlations, and outliers in the data for each parameter.

### 2. Feature Engineering
We created relevant features such as population density, input efficiency indices, price-to-yield ratios, and climate vulnerability scores.

### 3. Predictive Modeling
We performed predictive modeling sspecific to each item.
#### 3.1 Crop Price Prediction
- **Model:** Time Series Forecasting
- **Algorithm:** ARIMA (Autoregressive Integrated Moving Average).

#### 3.2 Population Growth Prediction
- **Model:** Time Series Forecasting
- **Algorithm:** ARIMA (Autoregressive Integrated Moving Average).

#### 3.3 Agricultural Input Efficiency
- **Model:** Time Series
- **Algorithm:** ARIMA (Autoregressive Integrated Moving Average) and SARIMA (Seasonal Autoregressive Integrated Moving Average).

#### 3.4 GDP Contribution Prediction
- **Model:** Time Series Forecasting and Regression
- **Algorithm:** ARIMA (Autoregressive Integrated Moving Average) 

#### 3.5 Climate Impact on Crop Yields
- **Model:** Time Series Forecasting and Regression.
- **Algorithm:** ARIMA (AutoRegressive Integrated Moving Average) for the rainfall and linear Regression for the temperature.

#### 3.6 Investment Recommendation System
- **Model:** Content-Based Filtering
- **Algorithm:** KilimoRiziki Recommender System, leveraging features identified through predictive models, bivariate, and univariate analysis.

## Recommender system
Using the predictive modelling tools, we managed to create a reccomender system that takes into account the risk criteria for each crop annually and per county. Here is a sample image to demonstrate the system.
![image](https://github.com/EvangelineNgunjiri/KilimoRiziki-Decision-Hub/blob/kagia/WhatsApp%20Image%202024-01-29%20at%2015.00.43.jpeg)

## Conclusion
The KilimoRiziki Decision Hub recommender system integrates risk criteria, offering precise investment recommendations for each crop annually and per county. This streamlined approach enhances decision-making, supporting sustainable growth in the agricultural sector.
