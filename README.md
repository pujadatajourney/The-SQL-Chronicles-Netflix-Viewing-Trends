# The-SQL-Chronicles-Netflix-Viewing-Trends
![](https://github.com/pujadatajourney/The-SQL-Chronicles-Netflix-Viewing-Trends/blob/main/logo.png)

## Overview
This project involves a comprehensive analysis of Netflix's movies and TV shows data using SQL. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Objectives
Analyzing the distribution of content types (movies vs TV shows).
Identifying the most common ratings for movies and TV shows.
Listing and analyzing content based on release years, countries, and durations.
Exploring and categorizing content based on specific criteria and keywords.

Dataset
The data for this project is sourced from the Kaggle dataset:
**Dataset Link:** [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)


## Schema

'''sqlDROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);'''


## Findings and Conclusion

Content Distribution: The dataset contains a diverse range of movies and TV shows with varying ratings and genres.

Common Ratings: Insights into the most common ratings provide an understanding of the content's target audience.

Geographical Insights: The top countries and the average content releases by India highlight regional content distribution.

Content Categorization: Categorizing content based on specific keywords helps in understanding the nature of content available on Netflix.

This analysis provides a comprehensive view of Netflix's content and can help inform content strategy and decision-making.

