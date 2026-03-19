# London Airbnb Price Analysis

An exploratory data analysis project investigating the key factors that influence Airbnb listing prices, with a focus on how pricing varies across neighbourhoods and room types.

## Overview

This project analyses Airbnb listings data to answer the question: **What drives Airbnb pricing, and how do prices vary across neighbourhoods?**

The analysis explores pricing patterns, identifies the most and least expensive areas, examines the relationship between listing features and price, and highlights trends that could be useful for both hosts and guests.

## Data

The dataset is sourced from [Inside Airbnb](http://insideairbnb.com/) and contains detailed information on Airbnb listings including price, location, room type, availability, and reviews.

## Methods

- **Data Cleaning:** Converted price from string format (e.g. `$150.00`) to numeric, handled missing values, and selected relevant features for analysis.
- **Exploratory Data Analysis (EDA):** Examined distributions, summary statistics, and identified outliers.
- **Visualisation:** Created bar charts, box plots, histograms, and heatmaps to uncover pricing patterns.
- **Statistical Analysis:** Used groupby aggregations and correlation analysis to explore relationships between price and listing features such as neighbourhood, room type, and number of reviews.

## Key Findings

- *Add your main findings here after completing the analysis*
- *For example: "Entire homes are on average 3x more expensive than private rooms"*
- *"The top 5 most expensive neighbourhoods are..."*
- *"There is a weak negative correlation between number of reviews and price"*

## Tools & Libraries

- Python 3
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Project Structure

```
airbnb-price-analysis/
├── data/
│   └── listings.csv
├── notebooks/
│   └── analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/airbnb-price-analysis.git
   ```
2. Install the required libraries:
   ```
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open the notebook:
   ```
   cd airbnb-price-analysis
   jupyter notebook notebooks/analysis.ipynb
   ```
