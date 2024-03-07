# Car Dataset Analysis and Visualization

## Overview

This Python script focuses on exploring and cleaning a car dataset, making it suitable for analysis and visualization. It utilizes Pandas for data manipulation, NumPy for numerical operations, and Matplotlib/Seaborn for creating visualizations. The script includes steps for handling missing values, data type conversions, and visualizing various aspects of the dataset.

## Dataset Information

The dataset used in this script is named 'cars_ds_final.csv'. It includes information about different car models, their features, and specifications.

## Data Cleaning

The script begins with data cleaning steps to address missing values, incorrect data types, and formatting issues. Key cleaning operations include:

- Renaming columns for clarity (`make` to `company`, `ex-showroom_price` to `price`).
- Handling missing values for specific columns.
- Converting price values to integers.
- Cleaning and converting columns related to cylinders, fuel tank capacity, city mileage, seating capacity, number of airbags, and basic warranty.
- Replacing missing values with appropriate default values.

## Data Exploration

The script explores the dataset by performing operations such as:

- Extracting and cleaning relevant columns for analysis.
- Checking unique values and handling missing values.
- Creating histograms and boxplots to visualize the distribution and outliers in the data.

## Data Visualization

The script uses Matplotlib and Seaborn to create various visualizations, including:

- A histogram plot to showcase the distribution of car companies.
- A boxplot to visualize the spread of car prices.
- A heatmap to display the correlation matrix of numerical columns.
- Scatter plots and line plots to show relationships between price, cylinders, and warranty by company and body type.

## Usage

1. Ensure that the required libraries (Pandas, NumPy, Matplotlib, Seaborn) are installed.
2. Download the 'cars_ds_final.csv' dataset.
3. Update the file path in the script to match the location of your dataset.
4. Run the script to perform data cleaning, exploration, and visualization.
