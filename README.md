# Task 1: Data Cleaning and Preprocessing

## Dataset
Netflix Movies and TV Shows (from Kaggle)

## Steps Performed
1. Loaded raw dataset and checked shape, nulls, and info.
2. Handled missing values:
   - Filled missing `country` with "Unknown".
   - Filled missing `date_added` with mode (most frequent).
   - Replaced missing `rating` with "Not Rated".
3. Removed duplicate records.
4. Standardized column names (lowercase, underscores).
5. Converted `date_added` to datetime and `release_year` to integer.
6. Standardized text values (`type`, `country`).
7. Exported cleaned dataset as `netflix_titles_cleaned.csv`.

## Outcome
- Clean dataset with no duplicates or missing critical values.
- Uniform column names and data types.
- Ready for analysis (e.g., content trends, country-wise distribution, rating analysis).
