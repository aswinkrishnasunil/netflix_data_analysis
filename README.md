# Netflix Titles Dataset Analysis

## Overview

This project involves the analysis of a dataset containing information about Netflix titles. We use Python's pandas library to perform various data analysis tasks on this dataset.

## Dataset

- Dataset Name: netflix_titles.csv
- Source: [Netflix Titles Dataset](https://www.kaggle.com/shivamb/netflix-shows)
- Description: This dataset contains information about movies and TV shows available on Netflix, including details like title, director, release year, and more.

## Code Overview

Here's a summary of the code snippets and data analysis tasks performed:

1. **Data Loading**: We imported the pandas library and loaded the dataset from the "netflix_titles.csv" file.

2. **Data Exploration**:
   - Displayed the first few rows of the dataset to get an overview of the data using `data.head()`.
   - Displayed the last few rows of the dataset using `data.tail()`.
   - Obtained the shape of the dataset (number of rows and columns) using `data.shape`.
   - Calculated the total size (number of elements) in the dataset using `data.size`.
   - Obtained the column names using `data.columns`.
   - Checked the data types of columns using `data.dtypes`.

3. **Data Cleaning and Analysis**:
   - Checked for duplicated rows using `data.duplicated()` and removed duplicates using `data.drop_duplicates()`.
   - Checked for missing values using `data.isnull()`.
   - Calculated the number of missing values in each column using `data.isnull().sum()`.

4. **Data Visualization**:
   - Visualized missing data using a heatmap with `seaborn` and `matplotlib`.
   - Plotted the count of movies and TV shows released each year using a bar chart.

5. **Filtering and Querying**:
   - Filtered data for specific titles like 'Zodiac', '30 Minutes or Less', and 'Ruben Fleischer'.
   - Filtered data for movies and TV shows released in India.
   - Filtered data for specific movie types and genres.

6. **Statistical Analysis**:
   - Calculated and displayed the count of movies and TV shows in the dataset.
   - Calculated the count of movies released in 2000.
   - Calculated the count of movies and TV shows from India.

## Usage

You can use this code and README as a reference for analyzing similar datasets or as a starting point for your data analysis projects.

## Author

- [ASWINKRISHNA SUNIL]
- [aswinkrishnasunil@gmail.com]

Feel free to reach out if you have any questions or need further assistance with the analysis.


