# Task 3: Exploratory Data Analysis (EDA) - Netflix Dataset

## Project Overview

This repository contains the final basic task for my Data Science internship. The objective was to perform a comprehensive Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset to uncover content strategies, production trends, and categorical relationships.

## Dataset Details

- **Source:** Kaggle (Netflix Movies and TV Shows)
- **Size:** 8,807 Rows | 12 Columns
- **Key Features:** Type (Movie/TV), Title, Release Year, Rating, Genre (Listed_in).

## Methodology & Tasks

### 1. Data Cleaning

- Handled missing values in `Director` and `Cast` by assigning "Unknown" placeholders.
- Imputed missing `Country` and `Rating` data using the Mode (most frequent value).
- Removed negligible null values in `Date_added` and `Duration` to ensure time-series accuracy.

### 2. Summary Statistics

- Generated descriptive statistics to understand the distribution of release years.
- Utilized `df.info()` and `df.describe()` to verify data types and range.

### 3. Correlation Analysis

- Performed cross-tabulation between **Content Type** and **Maturity Rating**.
- Created a **Heatmap** to visualize the relationship, revealing how Netflix targets different audience segments across Movies and TV Shows.

### 4. Trend Identification

- Analyzed production growth over the last decade (2010–2021).
- Visualized the shift in maturity ratings, identifying a sharp increase in **TV-MA** and **TV-14** content starting in 2015.

## Key Insights

- **The Maturity Shift:** Netflix has pivoted heavily toward adult-oriented content (TV-MA), which peaked in 2018.
- **Production Trends:** There was a massive spike in content additions post-2015, followed by a noticeable decline in 2021, likely due to global production halts.
- **Library Mix:** Movies still dominate the total count, but TV Shows show a more aggressive recent growth trend in mature categories.
