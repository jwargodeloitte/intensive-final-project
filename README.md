# intensive-final-project

## Overview
Given Computing Vision's request, our goal is to provide clarity to set a starting point to create a successful movie. The ==insert team name here== team worked a series of analysis to bring to you the choices for a great **director**, an epic **cast** and an the best movie **genre** that will guarantee to create a blockbuster film! 

### What is in the repository ?

The repository contains README file, .gitignore, 2 jupyter notebooks not in a folder, and 2 folders that also contain jupyter notebooks.

- The *README* (this file) shows in a high level what this project is about and what this repository contains.
- The *.gitignore* stores the data we utilized because it was too massive to unzip.
- Folder Archive contains two folders within that titled Analysis and Cleaning.
  - The Analysis folder contains all the analysis contributions from the team members to come to the final conclusions and recommendations.
  - Folder titled Cleaning contains all the data cleaning done initially, so the data can be more flexible to work with.
- The other Folder titled Figures contains the figures and other visuals that have been extracted to depict our findings.
- Jupyter notebook titled Data_Cleaning_Master contains the final data cleaning we did so the data can be utilized efficiently.
- Jupyter notebook titled Data_Analysis_Master that contains all the final data analysis 
- PowerPoint presentation titled *intensive-final-project* that contains our findings and research throughout this entire research.

## Business Understanding
### Current Situation 
The movie business has been growing fast during the last decade and with the appearance of streaming services, movies are becoming reachable to everybody. The competition is tough so only a few new movie studios succeed. 
### What can we do?
We can find out a simple formula to make a great movie!
### How are we doing it?
We have researched on different movie databases (that will be discussed in detail later), analyzed important metrics and found patterns with the help of statistics. 
As a data-driven team, we take decisions based on facts and we want to share this philosophy with CV. 

## Data Understanding Analysis 
The source of the data has come from many different areas. These different datasets include:
 - Box Office Moji
 - IMDB
 - Rotten Tomatoes
 - The Movie DB
 - The Numbers

The data from the sources is very succinct and valuable.  There are many possibilities and comparisons that can be done. Just a few categories include directors, producers, reviews, genres,  ratings, studios, theatre date, revenue, etc.

When one thinks of a movie the first thoughts that populate are who is being cast, who is putting it together, and what is the overarching theme?  To find the answer to these questions we will explore the data. 

### Who should be cast?
To understand who should be put in front of the camera it is important to look at popularity. To get a predictor of popularity our data scientists will analyze which actors have the most reviews. Out of the actors and actresses with the greatest number of reviews, we will order them to depict the top to least favorites by their average rating overall.

### Who should put it together?
To get an idea of who should be directing this movie, it is also necessary to look at popularity and reviews as well.  One way to see how favored a director is by looking at the Rotten Tomatoes dataset, specifically the fresh or rotton  data. This data is binary either yes, they are favored hence "fresh" or no they are not favored hence "rotten." Looking at the ratio of fresh to rotten can give us great insight on which director is highly favored. 

### What is the overarching theme?
Lastly, much of the time spent was researching which genre should the company invest in. The team wanted to find a genre that is highly favored, but not already oversaturated in the market. This again was looking at popularity of genres by counting all the movies that fall under each genre; as well as looking at the overall ratings of the movies in each genre.





## Statistical Communication 
### Recommendation 1

<img src="/Figures/director_vs_fresh.png" width=50% height=50%>

<img src="/Figures/director_vs_TotalNumberFreshReviews.png" width=50% height=50%>

### Recommendation 2

<img src="/Figures/cast_counts_hist.png" width=50% height=50%>

<img src="/Figures/cast_counts_average_ratings.png" width=50% height=50%>

<img src="/Figures/top10actors.png" width=50% height=50%>

<img src="/Figures/top10actresses.png" width=50% height=50%>

### Recommendation 3

<img src="/Figures/averageRatingPerGenre.png" width=50% height=50%>

<img src="/Figures/averageRatingOfMovie.png" width=50% height=50%>

## Conclusions 
