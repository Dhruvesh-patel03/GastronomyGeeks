# GastronomyGeeks
GastronomyGeeks is a data analysis project focused on uncovering insights from restaurant datasets. It explores trends in customer ratings, popular cuisines, and geospatial distributions, combining the art of gastronomy with the power of data science.

# Restaurant Dataset Analysis

## Overview
This project involves exploring and analyzing a restaurant dataset to derive insights about restaurant distributions, customer ratings, and geospatial relationships. The analysis is structured into three main sections: **Data Exploration and Preprocessing**, **Descriptive Analysis**, and **Geospatial Analysis**.

## Table of Contents
1. [Data Exploration and Preprocessing](#data-exploration-and-preprocessing)
2. [Descriptive Analysis](#descriptive-analysis)
3. [Geospatial Analysis](#geospatial-analysis)
4. [Technologies Used](#technologies-used)
5. [Setup and Installation](#setup-and-installation)
6. [Results and Insights](#results-and-insights)

---

## Data Exploration and Preprocessing
- **Dataset Structure**: Explore the dataset to identify the number of rows and columns.
- **Missing Data Handling**: Check for missing values in each column and handle them using imputation techniques or by removing incomplete rows, as appropriate.
- **Data Type Conversion**: Convert data types for columns where necessary to ensure consistency.
- **Target Variable Analysis**: Analyze the distribution of the target variable, `Aggregate Rating`, and address any class imbalances if identified.

## Descriptive Analysis
- **Statistical Measures**: Calculate key statistical measures (mean, median, standard deviation, etc.) for numerical columns.
- **Categorical Variable Exploration**: Analyze the distribution of categorical variables such as:
  - `Country Code`
  - `City`
  - `Cuisines`
- **Key Insights**:
  - Identify the top cuisines with the highest popularity.
  - Discover cities with the largest number of restaurants.

## Geospatial Analysis
- **Map Visualization**: Plot restaurant locations on a map using latitude and longitude data.
- **City and Country Distributions**: Analyze the geographic distribution of restaurants across different cities or countries.
- **Location-Rate Correlation**: Investigate potential correlations between restaurant locations and their ratings.

---

## Technologies Used
- **Programming Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Visualization Tools**: Matplotlib, Seaborn, Plotly
- **Geospatial Analysis**: Geopandas, Folium

---

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
