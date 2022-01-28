# Netflix Movies and TV Shows: Project Overview

## Quick Links
* [Project](https://htmlpreview.github.io/?https://github.com/melissawebbfl/Netflix-Movies-and-TV-Shows/blob/main/netflix_code.html)
* [Original data set](https://github.com/melissawebbfl/Netflix/blob/main/netflix_titles.csv)
* [Clean data set](https://github.com/melissawebbfl/Netflix/blob/main/netflix_titles_clean.csv)

## Introduction
<img src="https://cdn.pixabay.com/photo/2020/06/24/11/51/laptop-5335884_1280.jpg" width="320" height="256">  

This project involves data cleaning and visualization of a [Kaggle data set](https://www.kaggle.com/shivamb/netflix-shows) containing movies and TV shows available on Netflix.  

Here is a description of each of the original columns in the data set:

* `show_id`: unique ID for every movie/show
* `type`: identifies if the row represents a movie or show
* `title`: title of the movie/show
* `director`: list of directors of the movie/show
* `cast`: list of actors in the movie/show
* `country`: countries where the movie/show was produced
* `date_added`: date the movie/show was added on Netflix
* `release_year`: year the movie/show was actually released
* `rating`: MPA rating of the movie/show
* `duration`: total duration in minutes for movies, or number of seasons for shows
* `listed_in`: list of genres the movie/show falls under
* `description`: summary description provided for the movie/show

## Data Cleaning
I made the following changes to clean the data set:
* Identified and replaced incorrect values in columns
* Used a regular expression to convert `date_added` from a character type to a date type
* Replaced ratings that have the same meaning with a common value, so they're represented in one, standard way
* Made new columns for `duration` based on `type`


## Data Visualization
I created a few visualizations to summarize the data. Below are two of them.  

<img src="https://github.com/melissawebbfl/Netflix/blob/aae9756cb05e4360c70f00f4a19824c740379a87/top_10_countries.png" width="600" height="440">
<img src="https://github.com/melissawebbfl/Netflix/blob/aae9756cb05e4360c70f00f4a19824c740379a87/added_by_year.png" width="600" height="440">
