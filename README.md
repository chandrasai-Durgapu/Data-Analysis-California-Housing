# Data-Analysis-California-Housing
Exploratory Data Analysis on California Housing

## Overview
This project performs an in-depth Exploratory Data Analysis (EDA) and Feature Engineering study on the California Housing dataset. The primary goal is to understand the factors influencing median house values in California districts and prepare the data for subsequent machine learning model training.

## Key analyses performed:

Geographic Visualization: Mapping housing prices and population density across California.

Feature Distribution: Analyzing the spread and skewness of core numerical features.

Correlation Analysis: Identifying the strongest linear relationships between features and the target variable (Median House Value).

Feature Engineering: Creating new, predictive ratio features to improve model performance.
---
## Exploratory Data Analysis (EDA) & Key Findings
The EDA phase revealed crucial insights:

Geographic Price Clustering: Housing values are significantly higher near the coast, particularly in the major metropolitan areas like the Bay Area and Los Angeles/San Diego. Inland areas generally exhibit lower values.

Non-Linear Relationship: A clear cap exists on the median_house_value at $500,000, which required investigation and may necessitate data cleaning (truncation or removal) for proper modeling.

Strongest Predictors: The median income has the highest positive correlation with the target variable, confirming that economics is the dominant factor in home valuation.
---
## Feature Engineering
To better capture household-level statistics, the following new ratio features were calculated:

rooms_per_household: Total rooms divided by households (Average Rooms).

population_per_household: Total population divided by households (Average Occupancy).

bedrooms_per_room: Total bedrooms divided by total rooms (Indicator of house size quality/density).

These new features were analyzed via a correlation heatmap to ensure they provide additional predictive power beyond the raw feature counts.
---
## Technologies Used
Python

Pandas (Data manipulation and cleaning)

NumPy (Numerical operations)

Matplotlib (Basic plotting)

Seaborn (Advanced statistical visualization)
---
## Clone the repository
```bash
https://github.com/chandrasai-Durgapu/Data-Analysis-California-Housing.git
```
```bash
cd Data-Analysis-California-Housing
```

## Create Virtual Environment
```bash
python -m venv data-analysis-02housing
```

## Activate Virtual Environment
```bash
.\data-analysis-02housing\Scripts\activate
```

## Install Dependencies
```bash
pip install -r requirements.txt
```
---
## Visualisations:
present in images folder

