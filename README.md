This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a dataset containing details about Netflix titles, including both Movies and TV Shows. The goal is to uncover trends and insights such as the distribution of content types, popular genres, release patterns, and country-wise contributions to the Netflix library.

---

# Project Objective

To analyze and visualize key attributes of Netflix content to answer questions like:
- What is the ratio of Movies vs TV Shows?
- Which genres dominate the platform?
- What are the most frequent content ratings?
- How has content addition evolved over time?
- Which countries contribute the most content?
- What's the average duration of Movies vs TV Shows?

---

# Dataset

The dataset includes the following columns:
- **title** – Name of the show/movie
- **type** – Movie or TV Show
- **director** – Director of the title
- **cast** – Main actors/actresses
- **country** – Production country
- **date_added** – When it was added to Netflix
- **release_year** – Year of release
- **rating** – Content rating (e.g., PG, R, TV-MA)
- **duration** – Length of movie/show
- **listed_in** – Genre(s)

---

# Tech Stack

- **Python:** Core programming language
- **Pandas:** For data manipulation
- **Matplotlib & Seaborn:** For rich and aesthetic data visualization
- **Jupyter Notebook:** Interactive EDA environment

---

# EDA Steps

1. **Data Exploration**
   - Load dataset
   - Understand structure, data types, and value distribution

2. **Missing Value Handling**
   - Identify and manage null values appropriately

3. **Feature Engineering**
   - Extract new features like `year_added`, `month_added`, and `content_age`

4. **Univariate & Bivariate Analysis**
   - Count and compare Movies vs TV Shows
   - Top countries producing Netflix content
   - Most common genres and ratings
   - Year-wise and month-wise content addition trends

---

# Visualizations

- Content type distribution: 📺 TV Shows vs 🎥 Movies
- Year-wise and month-wise addition trends
- Top contributing countries
- Most popular genres
- Distribution of content ratings
- Average duration comparison between Movies and TV Shows

---

# Key Insights

- **Content Type:** Majority of titles are Movies, with a notable portion of TV Shows.
- **Genres:** Drama, Comedy, and Documentaries are the most common.
- **Year-wise Trends:** Most content was added in 2019 and 2020.
- **Ratings:** Common ratings include TV-MA, PG-13, and TV-PG.
- **Countries:** The United States leads in content count, followed by India and the UK.
- **Durations:** Movies generally have longer durations; TV Shows often span 1–3 seasons.

---

