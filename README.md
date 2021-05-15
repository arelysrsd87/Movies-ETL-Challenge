# Movies-ETL-Challenge
# Overview of the analysis
Amazing Prime Video team would like to develop an algorithm to predict which low budget film being released will become popular so that they can buy the streaming rights at a bargain. Amazing Prime has decide to sponsor a hackaton, providing a clean dataset of movies and asking participants to predict the popular films. We are tasked with helping create the dataset for the hackathon. There are two data sources: (1) a scrape of Wikipedia for all movies released since 1990, and (2) rating data from Movie Land's website. We will:
- extract the data from the two sources
- transform it into clean data set
- load that data set into a SQL table

## Purpose
Create an automated pipeline that takes in new data, performs the appropiate transformations, and loads the data into existing tables.