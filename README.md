This project performs an exploratory data analysis (EDA) on a dataset containing information about Netflix titles. The aim is to extract valuable insights regarding the distribution of content types, genres, ratings, and content additions over the years.

- Project Overview
The dataset provides information on various Netflix titles, including TV shows and movies. By analyzing this data, we aim to uncover patterns and trends such as:
The distribution of TV shows vs movies.
The most popular genres.
The most common ratings across content.
Trends in the number of titles added over the years.
Average duration of TV shows and movies.
The countries with the most content on Netflix.

- Dataset
The dataset used in this project is a collection of Netflix titles, which includes the following columns:
title: The title of the movie or TV show.
type: The type of content (e.g., Movie or TV Show).
director: The director of the movie or TV show.
cast: The cast members of the movie or TV show.
country: The country where the title was produced.
date_added: The date the title was added to Netflix.
release_year: The year the movie or TV show was released.
rating: The rating of the content (e.g., PG, R, etc.).
duration: The duration of the content (in minutes for movies, seasons for TV shows).
listed_in: The genre(s) of the title.

- Technologies Used
Python: Programming language used for data processing and analysis.
Pandas: For data manipulation and cleaning.
Matplotlib & Seaborn: For data visualization.
Jupyter Notebook: For interactive data analysis.

- Steps Performed in EDA
Basic Data Exploration: Loaded the dataset and checked its structure and summary statistics.
Handling Missing Values: Checked for missing values and handled them by filling or dropping based on context.
Feature Engineering: Created new columns like year_added and month_added for further analysis.
Exploratory Data Analysis:
Count the number of TV shows and movies.
Analyze the top countries with most titles.
Find the most common genres.
Distribution of ratings.
Analyze trends in content additions over the years.

- Visualizations:
Content type distribution (Movies vs TV Shows).
Year-wise content added.
Top countries with the most titles.
Common genres.
Rating distribution.
Average duration for movies and TV shows.

- Insights
Content Type: The majority of Netflix content consists of Movies, with a significant number of TV Shows.
Year-wise Additions: Most content was added to Netflix between 2019 and 2020.
Top Genres: The most common genres include Drama, Comedy, and Documentary.
Average Duration: TV Shows tend to have shorter durations compared to Movies.
Rating Distribution: There is a wide variety of ratings, with the majority being rated TV-MA, PG-13, and TV-PG.
