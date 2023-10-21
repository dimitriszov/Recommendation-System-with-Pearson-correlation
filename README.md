# Recommendation System with Pearson Correlation

This repository contains code for a recommendation system that uses Pearson Correlation. The code is based on the following original file on Kaggle: [Original File](https://www.kaggle.com/code/dimitriszov/recommendation-system-with-pearson-correlation)

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Data](#data)
- [Data Mining](#data-mining)
- [Authors and Categories](#authors-and-categories)
- [Distribution of Ratings](#distribution-of-ratings)
- [Pearson Correlation](#pearson-correlation)
- [Results](#results)

## Introduction

This code implements a recommendation system based on Pearson Correlation. It reads data about books and user ratings and provides recommendations for users based on their past ratings.

## Requirements

To run this code, you'll need the following libraries:

- pandas
- plotly
- math

You can install these libraries using pip:
```
pip install pandas plotly
```
## Data

The data used for this recommendation system is stored in CSV files taken from the Kaggle dataset [Amazon Books Reviews](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews):

- `books_data.csv`: Contains information about books, including title, authors, and categories.
- `Books_rating.csv`: Contains user ratings for books.

## Data Mining

The code performs various data mining tasks, including:
- Identifying books with the most ratings.
- Finding books with the highest average ratings.
- Analyzing authors with the most books.
- Analyzing categories with the most titles.
- Visualizing the distribution of ratings.

## Pearson Correlation

The core of this recommendation system is based on Pearson Correlation. It calculates the similarity between users and suggests books that similar users have rated highly.

## Results

The code provides recommendations for users based on their input ratings. You can find the top recommended books in the `recommendation_df` dataframe. You can fide all the results in the [Kaggle notebook](https://www.kaggle.com/code/dimitriszov/recommendation-system-with-pearson-correlation) I have created.



