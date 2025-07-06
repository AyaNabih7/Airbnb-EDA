# Airbnb EDA – Exploratory Data Analysis on NYC Listings

This repository contains an exploratory data analysis (EDA) project focused on Airbnb listings in New York City. The analysis was originally developed in a Kaggle notebook and aims to extract insights from the dataset through data cleaning, visualization, and statistical summarization.

## 📌 Project Overview

Airbnb has become a popular platform for short-term rentals across major cities. Understanding listing prices, location trends, availability, and customer engagement can offer valuable insights to hosts, travelers, and business analysts.

This notebook:
- Provides an overview of the dataset.
- Identifies patterns and trends in price, location, and room types.
- Visualizes geospatial data for better understanding of NYC listings.

## 📊 Dataset

**Source**: [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

**Description**: This dataset includes over 48,000 listings in NYC with features such as:
- `name`, `host_name`, `neighbourhood`, `latitude`, `longitude`
- `room_type`, `price`, `minimum_nights`, `number_of_reviews`
- `availability_365`, and more.

## 🔍 Analysis Highlights

- **Top Hosts**: Hosts with the highest number of listings.
- **Room Type Distribution**: Comparison between entire home/apt, private room, shared room.
- **Price Analysis**: Distribution of prices and outlier detection.
- **Geospatial Visualization**: Mapping listings by borough using `folium`.
- **Correlation Analysis**: Insights from relationships between numerical features.

## 📁 Files

- `airbnb-eda.ipynb`: Main Jupyter Notebook with all EDA steps and visualizations.
- `README.md`: Project description and overview.

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `folium`
- `plotly`
- `warnings`

## 📌 How to Run

To run the notebook locally:

1. Clone the repository.
2. Install required libraries using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn folium plotly
