## Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to understand the composition of Netflix's content library. The analysis uncovers trends in content types, release years, countries, genres, ratings, and durations through data cleaning, statistical summaries, and visualizations.
The objective is to transform raw data into meaningful business insights that can support content strategy and audience analysis. The commonly used dataset contains metadata such as title, type, director, cast, country, release year, rating, duration, and genre.

Dataset Name: Netflix Movies and TV Shows
Source: Kaggle

## The dataset contains information about Netflix titles, including
- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

## Objectives
- Clean and preprocess the dataset
- Handle missing values and duplicates
- Explore the distribution of Movies and TV Shows
- Analyze yearly content growth
- Identify top producing countries
- Study content ratings
- Analyze movie durations and TV show seasons
- Explore the most common genres
- Generate visualizations for business insights

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning
The following preprocessing steps were performed:

- Removed duplicate records
- Checked for missing values
- Converted date_added into datetime format
- Extracted:
- Year Added
- Month Added
- Standardized categorical columns
- Cleaned duration values
- Split multi-value columns where necessary

## Exploratory Data Analysis
The project answers several key questions:

# Content Distribution
- Movies vs TV Shows
- Percentage of each content type
# Release Trend
- Number of titles released each year
- Growth of Netflix content over time
# Country Analysis
- Countries contributing the most content
- Top 10 content-producing countries
# Genre Analysis
- Most popular genres
- Genre frequency distribution
# Ratings Analysis
- Distribution of content ratings
- Most common audience categories
# Duration Analysis
- Movie duration distribution
- TV show season distribution
# Content Added Analysis
- Number of titles added by year
- Monthly content additions

## Key Insights

- Movies make up a larger share of the Netflix catalog than TV Shows.
- Netflix experienced rapid content growth after 2015.
- The United States contributes the highest number of titles.
- Drama and International Movies are among the most common genres.
- Most movies have a runtime between 90 and 120 minutes.
- The majority of TV Shows contain 1 season.
- Content additions increased significantly during Netflix's global expansion years.

## Visualizations
The project includes visualizations such as:

- Count plots
- Bar charts
- Pie charts
- Histograms
- Box plots
- Word Cloud

## Project Structure

```text
Netflix-EDA/
├── .gitignore
├── EDA_on_Netflix_titles.ipynb
├── README.md
├── requirements.txt
```
