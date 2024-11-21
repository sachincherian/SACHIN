# Google Play Store App Analysis

This project provides an analysis of apps available in the Google Play Store dataset. The analysis includes data cleaning, exploratory data analysis, and visualization of key metrics like ratings, installs, and app types.

## Project Description

The dataset contains information about various apps available on the Google Play Store, including details such as app name, category, rating, number of reviews, size, and more. The goal of this analysis is to explore how different factors (such as app type, rating, and number of installs) are related to each other, and to generate insights from the data.

The R script provided processes the dataset, performs basic cleaning, and generates three visualizations:
1. **Histogram of App Ratings by Type (Free vs. Paid)**
2. **Boxplot of Ratings by App Type**
3. **Scatter Plot of Ratings vs. Installs**

## Files Included

- **R Script**: `analysis.R` – This script loads the dataset, cleans it, and creates visualizations.
- **Plots**:
  - `histogram.png`: A histogram showing the distribution of app ratings, divided by app type (Free or Paid).
  - `boxplot.png`: A boxplot visualizing the spread of ratings by app type.
  - `scatter_plot.png`: A scatter plot showing the relationship between app ratings and the number of installs.

## Dataset

The dataset is a CSV file named `GooglePlayStoreApps.csv`. It contains the following columns:

- `App`: Name of the app.
- `Category`: The category to which the app belongs.
- `Rating`: Average user rating of the app.
- `Reviews`: Number of reviews.
- `Size_in_MB`: Size of the app in MB.
- `Installs`: Number of installs.
- `Type`: Whether the app is free or paid.
- `Price`: Price of the app.
- `Content Rating`: Age group that the app is rated for.
- `Genres`: Genres associated with the app.
- `Last Updated`: Date when the app was last updated.
- `CURRENT_VERSION`: The current version of the app.
- `ANDROID_VERSION`: Minimum Android version required for the app.

## How to Run the Code

To run the R script and generate the plots, follow these steps:

1. **Install Required Packages**:
   If you don't have the required packages installed, you can install them using the following commands in R:
   
   ```R
   install.packages(c("dplyr", "ggplot2", "tidyr", "readr", "ggpubr"))
