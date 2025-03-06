# IMDB-Movie-Analysis

# Project Overview
This project explores and analyzes the IMDB Movies dataset to uncover insights into movie trends, genre popularity, and factors influencing movie success. By leveraging Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib, the analysis aims to answer key business questions and deliver actionable recommendations for IMDB to better understand its data.

Dataset: https://drive.google.com/file/d/1lruT50ZWD4PtvDbIn4VnepZvSoeO9BrA/view?usp=sharing

# Dataset Information

Dataset: IMDB Movies Dataset

Each row represents a movie.

Each column contains attributes like budget, revenue, genre, ratings, release year, and more.

# Key Libraries Used

Pandas: For data manipulation and cleaning.

NumPy: For numerical operations and handling missing values.

Matplotlib: For creating static visualizations.

Seaborn: For advanced statistical visualizations.

# Steps and Questions Addressed
1.Data Overview and Basic Exploration

&#8226; Used .info() to examine data types and detect missing values.

&#8226; Generated summary statistics using .describe() to understand numerical columns.

&#8226; Identified potential data quality issues like missing values, incorrect data types, and outliers.

2.Data Cleaning

&#8226; Handled missing values appropriately, depending on their importance and significance.

&#8226; Converted data types (e.g., dates and numeric fields) for accurate analysis.

&#8226; Addressed outliers in numerical columns such as budget and revenue.

3. Univariate Analysis

&#8226; Analyzed the distribution of scores using histograms.

&#8226; Identified the most common genres using bar charts.

4.Bivariate Analysis

&#8226; Explored Budget vs. Revenue using scatter plots.

&#8226; Analyzed how ratings vary by country using box plots.

&#8226; Calculated correlation coefficients to determine relationships between scores, budgets, and revenues.

5.Genre-Specific Analysis

&#8226; Determined the genre with the highest average rating.

&#8226; Visualized genre popularity over time by plotting the number of movies released per genre each year.

6.Year and Trend Analysis

&#8226; Examined how average movie ratings changed over the years using line plots.

&#8226; Identified years with the highest and lowest movie releases using bar plots.

7.Multivariate Analysis

&#8226; Identified the most popular genres in each decade using bar plots.

&#8226; Analyzed the relationship between genre, release year, and average ratings.

# Key Insights

Genre Popularity:
Some genres consistently receive higher ratings, while others dominate in number of releases.

Budget vs. Revenue:
There is a positive correlation between a movie's budget and revenue, meaning higher-budget movies tend to earn more.

Trends Over Time:
Both average ratings and genre popularity have shifted significantly over different decades.



