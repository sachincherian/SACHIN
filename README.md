# Google Play Store App Analysis

This project provides an analysis of apps available in the Google Play Store dataset. The analysis includes data cleaning, exploratory data analysis, and visualization of key metrics like ratings, installs, and app types.

## Project Description

The dataset contains information about various apps available on the Google Play Store, including details such as app name, category, rating, number of reviews, size, and more. The goal of this analysis is to explore how different factors (such as app type, rating, and number of installs) are related to each other, and to generate insights from the data.

The R script provided processes the dataset, performs basic cleaning, and generates three visualizations:
1. **Histogram of App Ratings by Type (Free vs. Paid)**
2. **Boxplot of Ratings by App Type**
3. **Scatter Plot of Ratings vs. Installs**

Description of Visualizations
Histogram of App Ratings by Type: This histogram shows the distribution of app ratings for both Free and Paid apps. The ratings are divided into different bins to better understand the frequency of various rating ranges.

Boxplot of Ratings by App Type: This boxplot compares the ratings of Free and Paid apps, allowing us to see the median, interquartile range, and potential outliers for both app types.

Scatter Plot of Ratings vs. Installs: This scatter plot visualizes the relationship between the number of installs and the average rating of the apps. A linear regression line is also added to show the trend.
