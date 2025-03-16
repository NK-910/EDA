# Spotify Songs Data Analysis

## Project Overview

This project explores the **Spotify dataset**, analyzing various musical aspects such as **song popularity, duration, loudness, explicit content**, and more. The goal is to uncover trends and insights in music data through **Exploratory Data Analysis (EDA)** and visualization.

## Key Steps in Analysis

1. **Understanding the Data**

   - Checking data structure, types, missing values, and duplicates.
   - Initial exploration using `df.info()`, `df.describe()`, and `df.head()`.

2. **Data Cleaning & Preprocessing**

   - Handling missing and duplicate values.
   - Converting categorical features and standardizing formats.
   - Fixing anomalies (e.g., explicit content labeling, mode representation).
   - **Removed years 1998 and 2020 as outliers since 1998 contained only one song and 2020 contained only three songs.**

3. **Exploratory Data Analysis (EDA)**

   - **Univariate Analysis**: Analyzing individual features (popularity, danceability, duration, etc.).
   - **Bivariate Analysis**: Investigating relationships (e.g., popularity vs. duration, loudness over years).
   - **Time Series Trends**: Examining how explicit content, loudness, and other attributes change over time.
   - **Correlation Analysis**: Using heatmaps to identify strong and weak correlations between features.

4. **Data Visualization**

   - Histograms, box plots, and scatter plots to uncover distributions.
   - Line charts for trends over the years.
   - Pie charts for categorical breakdowns (e.g., genre distribution).

5. **Key Insights & Findings**

   - **Pop is the most popular genre, making up 46.9% of the dataset.**
   - **Rihanna is the most frequent artist, appearing in 25+ songs.**
   - **The song "Sweater Weather" is the most popular track in the dataset.**
   - **Danceability does not have a strong correlation with song popularity.**
   - **Explicit content in songs has increased significantly over the years.**
   - **Loudness levels have decreased with time, suggesting changes in production styles.**
   - **Most popular songs tend to have durations between 3-4 minutes.**

## Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** for interactive analysis

## Dataset

- The dataset consists of multiple attributes describing songs, such as:
  - `artist`, `song`, `year`, `popularity`, `danceability`, `energy`, `loudness`, `explicit`, `mode`, `tempo`, and `genre`.

## How to Use

1. **Install Dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
3. **Follow the step-by-step analysis in the notebook.**

## Future Enhancements

- Adding **Machine Learning models** to predict song popularity.
- Exploring **genre-based trends** in depth.
- Incorporating **Spotify API** for real-time data analysis.

**Author:** Naira Khaled\
**Date:** 16/3/2025\
**Contact:** [nairakhaled1010@gmail.com](mailto\:nairakhaled1010@gmail.com)

---

