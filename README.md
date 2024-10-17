# Introduction
This project involves creating an interactive movie analysis dashboard using Microsoft Power BI. The dashboard will provide comprehensive insights into the movie industry, focusing on key metrics like movie ratings, genres, gross revenue, and budget performance. By analyzing these aspects, users will be able to explore trends, patterns, and insights about the performance of movies over time, as well as other factors like votes, directors, and runtime.

# Objectives
The primary objective is to analyze the movie dataset effectively and generate strategic insights through a user-friendly Power BI dashboard. The goal is to help stakeholders understand the factors contributing to movie success, track budget and revenue trends, and identify key players like directors, stars, and production companies influencing the movie’s success.

# Process Overview

* **Data Preparation:**

  - Data Import and Transformation: Imported the movie dataset using Power BI's Power Query. Performed data cleaning such as removing duplicates and irrelevant columns, and standardizing the data formats (e.g., year, runtime, budget).
  - Data Model: Organized the dataset into fact and dimension tables (movies, directors, genres) to streamline analysis. Added a date table for year-based filtering and time-series analysis.

* **Building the Data Model:**

  - Create Relationships: Established relationships between columns such as movie names, directors, genres, and companies to facilitate easy data exploration.
  - Date Table: Introduced a date table to allow for the analysis of movies released over time.
  - Create Hierarchies: Established hierarchies for year, genre, and director to drill down for more granular analysis.

* **Calculating Key Metrics:**

  - DAX Calculations: Computed essential movie performance metrics using Data Analysis Expressions (DAX) such as:
  - Total Gross Revenue: Sum of gross revenue for each movie.
  - Average Rating: Average rating of all movies.
  - Budget Utilization: Difference between budget and gross revenue.
  - Top Movies: Based on ratings, revenue, and votes.
  - Votes Per Movie: Total votes per movie to assess audience engagement.

* **Dashboard Design:**

  - Interactive Elements: Added slicers to filter movies by genre, country, year of release, and director for dynamic exploration.
  - Data Visualizations: Designed custom charts such as:
  - Bar charts: To show top-grossing movies or highest-rated directors.
  - Line charts: These are used to track revenue trends over the years.
  - Pie charts: To display the distribution of movie genres.
  - Heatmaps: To visualize the correlation between budget and gross revenue.
  - Conditional Formatting: Used formatting to highlight outlier movies based on high budget but low gross revenue, or high ratings with low votes.

# Tools Used

. **Excel:** For initial data cleaning and formatting.
. **SQL:** This is used to run queries on the dataset to answer key questions about the data.
. **Power Query:** This is for data transformation and combining columns like budget and revenue.
. **Power BI:** For interactive data visualization and dashboard creation.

# Conclusion
The interactive movie analysis dashboard built in Power BI provides essential insights into the performance of movies, allowing data-driven decision-making. The dashboard’s dynamic interface enables users to filter and explore critical movie metrics such as gross revenue, ratings, and audience engagement.

# Insights from Dashboard Charts

  - **Genre Popularity:** Certain genres consistently perform better in terms of ratings and gross revenue, indicating viewer preferences.
  - **Revenue and Budget Trends:** Movies with high budgets do not always correlate with high gross revenue, revealing budget inefficiencies in some cases.
  - **Top Directors and Stars:** Specific directors and actors are consistently associated with higher-rated and higher-grossing movies.
  - **Yearly Movie Trends:** Year-over-year movie releases can show trends in genres, budgets, and overall industry performance.
  - **Audience Engagement:** Movies with a higher number of votes often correlate with higher gross revenue, showcasing the impact of audience size on a movie's financial success.
