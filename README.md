# Data-Cleaning-and-Preprocessing
# Task 1

## Dataset
-Netflix Movies and TV Shows

## Tools Used
-Google Colab
-Python,Pandas

## Cleaning Steps Performed
-Dropped duplicate rows
-Standardized column names
-Filled missing values:
  - director, cast, country-> "Unknown"
  - rating->"Not Rated"
  - duration->"Unknown"
  - description->"No description"
-Converted date_added to datetime format
-Standardized text fields (type, country, rating)
-Made release_year integer

## Result
-Cleaned dataset: netflix_titles_clean.csv
