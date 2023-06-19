# Investigating-the-TMDB-movie-dataset

# Introduction
In this project, we will be exploring a movie dataset provided by Kaggle and cleaned by Udacity. Our goal is to investigate which factors make a movie successful or unsuccessful. We will be using pandas and numpy packages for calculations and dataframe manipulations, as well as seaborn and matplotlib for data visualizations.

# Table of Contents
Introduction
Data Wrangling
Exploratory Data Analysis
Conclusions
Limitations


# Data Wrangling

I started by getting an overview of the dataset using pandas. I then identified the columns that will not be used in our analysis and removed them for a cleaner and easier data analysis. I also removed null values in director, overview, and genres, and dropped the cast column as it was not necessary for our exploration. I also removed duplicates and replaced null values. Finally, I changed the data type of the release_date and release_year columns to make them easier to work with.


# Exploratory Data Analysis
I explored the dataset by answering two questions:

### Which genres had the largest release of movies (or the most popular genre)?
### Which year has the highest release of movies?

I found that Drama is the most popular movie genre followed by comedy, and Western, War, and Foreign have the least made movies and are the least popular genres. I also found that 2014 had the highest release of movies, followed by 2013 and 2015. I noticed a gradual increase and saturation in movie releases year after year, and the year with the least movies released is 1961 and 1969.


# Conclusions
From our analysis, I can conclude that movie genres can play a significant role in their success or failure. Additionally, I can see that the movie industry has been growing year after year, with some years having more releases than others.


# Limitations
It's important to note that this analysis is only based on a small dataset and is not a reliable source. I did not perform any advanced statistics, and I removed null or unidentified values, which could have affected our results.
