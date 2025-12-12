# Crypto Market Analysis using Power BI

This project presents a comprehensive descriptive analysis of the cryptocurrency market using Microsoft Power BI. It focuses on exploring historical price data, trading volume, market capitalization, volatility, and monthly returns of multiple cryptocurrencies. The project also integrates external market sentiment data to provide deeper analytical insights.

---

## 📌 Project Overview

The main objective of this project is to analyze cryptocurrency market behavior using business intelligence techniques. Through data cleaning, descriptive analysis, and interactive dashboard design, the project enables users to explore market trends, compare cryptocurrencies, and understand risk–return characteristics.

Key goals include:
- Understanding price trends over time
- Comparing average prices, trading volume, and market capitalization
- Analyzing volatility and monthly returns
- Exploring relationships between trading volume and price
- Integrating market sentiment using the Crypto Fear & Greed Index

---

## 📊 Tools and Technologies

- **Microsoft Power BI**
- **Power Query Editor** (data cleaning and transformation)
- **DAX (Data Analysis Expressions)**
- **JSON Web API** (Crypto Fear & Greed Index)
- **LaTeX** (academic report)

---

## 🧩 Dataset Description

The dataset contains historical information for multiple cryptocurrencies, including:

- Date
- Symbol
- Open, High, Low, Close prices
- Trading Volume
- Market Capitalization

Additional sentiment data was retrieved from:
- **Crypto Fear & Greed Index API**  
  https://alternative.me/crypto/fear-and-greed-index/

---

## 🧹 Task I: Data Preparation and Cleaning

Data preparation was performed using Power Query Editor and included:
- Removal of null and missing values
- Data type conversion for numeric and date fields
- Cleaning and standardization of cryptocurrency symbols
- Date format correction
- Column renaming using consistent lowercase naming conventions

This step ensured error-free data loading and reliable analysis.

---

## 📈 Task II: Descriptive Data Analysis

The following analyses were conducted:
- Price trend analysis over time (Line charts)
- Average price comparison across cryptocurrencies (Column charts)
- Volatility analysis based on price fluctuations (Bar charts)
- Relationship between trading volume and closing price (Scatter plots)
- Maximum and minimum price analysis (KPI cards)
- Monthly return analysis using DAX calculations (Line charts)

---

## 🖥️ Task III: Dashboard Design

The Power BI report consists of four interactive dashboard pages:

1. **Overview Dashboard**  
   High-level market indicators and recent performance metrics

2. **Price Trends Dashboard**  
   Temporal analysis of prices, volatility, and monthly returns

3. **Comparison Dashboard**  
   Side-by-side comparison of volume, price, and market capitalization

4. **Insights Dashboard**  
   Advanced visualizations including scatter plots and combined charts

Each dashboard page is designed to support intuitive exploration and data-driven decision-making.

---

## 🧠 Task IV: DAX Calculations and Advanced Features

Key DAX measures and features include:
- Volatility calculation
- Average closing price
- Monthly return calculation
- Conditional formatting for gains and losses
- Integration of the Crypto Fear & Greed Index via Web API

These enhancements increase the analytical depth and usability of the dashboards.




