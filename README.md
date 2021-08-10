# Title

**Authors**: Daniel Ross-Leutwyler

## Overview

In this project I will make suggestions about what sort of movies Microsoft should begin making for the launch of their movie studio. I will use the provided dataset, supplemented when needed by other publicly available datasets, cleaning and collating it as necessary, and making plots and charts that we can make inferences from.

## Business Problem

"Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create."

There are lots of metrics to measure success, some are easier to objectively measure than others. With the data at hand the two main ways to judge the success of a movie are through analyzing key financial metrics (gross box office, and return-on-investment, for example), and critical response (as aggregated by the IMBD website). 

By analyzing what, if any, attributes the top grossing movies all share, we can make informed suggestions about what sort of film Microsoft should pursue.

I will also explore the relationship between genre, budget, and gross revenue. The success of a blockbuster is in part dependent upon its ROI, as well.

The analysis performed here will attempt to answer these three questions:

Q1) What are the highest grossing genres from 2010-2018?

Q2) What genres have the highest revenue and ,ROI, over that same time frame?

Q3) Which genres have a lower production budget and a higher ROI

These questions will help Microsoft make business savvy decisions about their entry into a crowded market.

## Data

The data being used for this project is taken from IMBD, Box Office Mojo (also part of IMDB), and The Numbers database.

The relevant data I am looking at contains information about the movie name, the year it was made, the genre, domestic and foreign sales, the budget, and the ranting and number of votes on IMDB.

I will filter and clean this data to create plots that describe the relationship between genre and gross sales, rating and gross sales, and genre and ROI.


## Methods

The data requires some cleaning, merging, and aggregation to allow descriptive analysis.

## Results

Q1) The highest grossing genres from 2010-2018 are Sci-fi, adventure, and animation.

Q2) The genres with highest revenue are animation, sci-fi, and adventure. The genres with the highest ROI are mystery, horror, and thriller.

Q3) The genres with the lowest production budget and highest ROI are mystery, horror, and thriler.

## Conclusions

In this project I have analyzed, cleaned, and interpreted data in order to make suggestions about what types of movies Microsoft should be making for the launch of their new movie studio.

The two primary metrics used to measure success in this project are 'total gross sales' (domestic box office gross + foreign box office gross) and return on investment ((total gross sales - production budget) / production budget).

Using these metrics I have determined that the genres of movie with the highest total gross sales are:

Sci-Fi\
Adventure\
Animation

However, during the investigation of top grossing films, it is clear that the majority of these movies are part of a series. Unless there is a home-run series that Microsoft already has in its back pocket, it is unreasonable to expect that a new series would immediately be a commercial success.

Upon examining the ROI plotted against production budget, it becomes clear that certain genres of movie have a higher ROI than others. These genres, having the most 'bang for the buck are:

Horror
Musicals
Sport
Animation

These are the types of movies that I think it is most prudent for Microsoft to make. Animation, especially, has a very broad appeal, and does well as a genre in terms of commercial success.



## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── project_1_final.ipynb               <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── zippeddata                          <- Both sourced externally and generated from code
└── old_scratchpads                     <- .ipynb used to build final notebook
└── old_files                           <- files not relevent to the finished notebook