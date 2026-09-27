# Tartu Apartment Rent Prediction

This repository contains the data and code for predicting apartment rental prices in Tartu, Estonia. It is a group project for the **Machine Learning (MTAT.03.227)** course at the University of Tartu (Autumn 2026).

## Dataset
Since there are no open public datasets for the Tartu real estate market, we created a custom dataset by scraping current listings from the KV.ee real estate portal. 

The data is divided into two folders:
* `raw/` - The original scraped CSV files.
* `clean/` - The preprocessed and cleaned datasets used for machine learning.
  * **tartu_basic.csv** - Contains basic features: `Price`, `Size`, `Rooms`, and `Neighborhood`.
  * **tartu_extra.csv** - Contains basic features + engineered binary features extracted from listing descriptions (e.g., `New_Renovated`, `Furnished`, `Balcony_Terrace`, `Sauna`, `Parking`).

