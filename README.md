# Movie-data-analysis

An easy-to-read analysis of 10,000+ movies (1960–2015) using Python. This project looks at what makes movies make money, which genres perform best, and how movie trends changed over time.

# What is This Project About?
This project uses data from The Movie Database (TMDb) to answer basic business questions about the movie industry. The main goal is to find out what drives box office success and profit.

# Key Questions Asked
Money: Does spending more money on a movie mean making more money back?
Genres: Which movie types (like Action or Animation) make the most money?
Ratings: Do highly-rated movies always become popular and make the most money?
Time: How have movie lengths and the number of movies made changed over the years?

# About the Data
File: tmdb-movies.csv
Total Movies: 10,866 movies
Main Information: Title, Budget, Revenue, Ratings, Popularity, Genres, Release Date, and Runtime.

# How the Data Was Cleaned
Before analyzing the data, it was cleaned using Python:

# Removed repeated (duplicate) movies.
Filled in missing information like missing director or actor names with 'Unknown'.
Filtered out movies with $0 recorded budget or revenue so calculations stayed accurate.
Created new columns for Profit (Revenue - Budget) and ROI (Return on Investment).
Split lists of genres so each genre could be counted individually.
