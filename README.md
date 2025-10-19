Netflix Data Analysis Project

Overview

This project aims to analyze and visualize relationships between various datasets related to Netflix viewing hours and IMDb ratings. The data is cleaned and transformed using pandas, stored in an SQLite3 database, and visualized using seaborn and matplotlib.

Table of Contents

Project Description
Datasets
Setup
Data Cleaning and Transformation
Database Creation
Data Visualization
Conclusions

Project Description:

In this project, we utilize three datasets: "What We Watch on Netflix" (Excel format), IMDb ratings (TSV format), and IMDb titles (TSV format).
Clean and transform the datasets using pandas.
Create a database using these datasets as tables with SQLite3.
Visualize different relationships between the tables using seaborn and matplotlib.

Datasets:

What We Watch on Netflix: This dataset contains information about the hours viewed for various titles on Netflix.
IMDb Ratings: This dataset contains user ratings for various titles.
IMDb Titles: This dataset contains information about the titles such as genres, release dates, etc.

Setup:

To set up this project, follow these steps:

Clone the repository:
```sh
git clone https://github.com/Arnaudnyssen/Netflix_project.git
cd netflix-data-analysis
```
Install the necessary dependencies:
```sh
pip install pandas seaborn matplotlib sqlite3
```
Data Cleaning and Transformation:

The datasets are cleaned and transformed using pandas. This involves:

Reading the datasets from their respective formats (Excel and TSV).
Handling missing values and duplicates.
Merging datasets to create a comprehensive dataset for analysis.

Database Creation:

Using SQLite3 database to store the cleaned datasets as tables. This involves:Connecting to SQLite3.
Creating tables and inserting data into the tables.

Data Visualization:

Using seaborn and matplotlib, various relationships between the datasets are visualized, such as:

The average hours viewed by rating.
The distribution of ratings.
The relationship between title genres and hours viewed.
Conclusions

From the visualizations, we can infer various trends such as:

Higher rated titles tend to have more viewing hours.
Certain genres are more popular and have higher viewing hours.
