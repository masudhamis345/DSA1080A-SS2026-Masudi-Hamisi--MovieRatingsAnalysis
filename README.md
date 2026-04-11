# Movie Ratings & User Behavior Analysis

- Masudi Hamisi – 676797

## Dataset
- Source: https://grouplens.org/datasets/movielens/
- Number of rows: 45,433
- Number of columns: 35+

## Project Overview
This project analyzes movie ratings and user behavior using the MovieLens dataset. It aims to identify patterns in how users rate movies and how popularity influences ratings.

## Objectives
- Analyze rating distribution
- Identify top-rated movies
- Identify most popular movies
- Understand trends over time
- Study user rating behavior

## Data Sources
- movies_metadata.csv
- ratings_small.csv
- links.csv
- keywords.csv
- credits.csv

## Variable Description
- title: Name of the movie
- avg_rating: Average rating of the movie
- rating_count: Number of ratings per movie
- release_date: Date the movie was released
- year: Extracted year from release date
- age: Age of the movie
- director: Movie director

## Methodology
- Data cleaning: handled missing values and corrected data types
- Data merging: combined multiple datasets using IDs
- Feature creation: created avg_rating and rating_count
- Exploratory Data Analysis: created visualizations using matplotlib

## Key Findings
- Most movies have moderate ratings
- Popular movies have more stable ratings
- Weak correlation (0.14) between rating and popularity
- Movie production has increased over time
- Movies with few ratings are less reliable

## Recommendations
- Focus on movies with many ratings for reliable analysis
- Promote highly rated but less popular movies
- Analyze trends over time to understand user preferences

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Conclusion
The analysis shows that user ratings are generally moderate and that popularity does not strongly influence ratings. These insights can help improve recommendation systems and better understand audience behavior.
