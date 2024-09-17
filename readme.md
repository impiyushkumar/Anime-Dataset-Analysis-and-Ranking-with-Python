# Anime Dataset Analysis and Ranking with Python

## Project Overview

This project involves analyzing and ranking anime based on a dataset (`anime.csv`) using Python libraries like **Pandas** and **NumPy**. The goal is to manipulate the dataset, clean the data, and perform exploratory analysis to rank the anime based on criteria such as popularity, rating, and genre.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)

## Dataset

The dataset used in this project is `anime.csv`, which contains the following columns:
- **anime_id**: Unique identifier for each anime
- **name**: Title of the anime
- **genre**: Genres associated with the anime
- **type**: Format (TV, Movie, OVA, etc.)
- **episodes**: Number of episodes
- **rating**: Average user rating for the anime
- **members**: Number of users who have interacted with the anime


## Project Structure

- `anime.csv`: The dataset containing anime data
- `DSproject.ipynb`: Main script for data analysis and ranking
- `README.md`: This README file

## Features

1. **Data Loading**: Load the `anime.csv` dataset using Pandas.
2. **Data Cleaning**: Handle missing or inconsistent data (e.g., missing ratings, undefined genres).
3. **Data Exploration**:
    - Display basic statistics on the dataset (mean, median, mode).
    - Analyze the distribution of genres, types, and ratings.
4. **Anime Ranking**:
    - Rank anime based on their average user rating.
    - Rank anime based on the number of user interactions (members).
    - Generate a combined ranking using weighted scores (rating and members).
5. **Data Visualization**: (Optional) Visualize the top anime using matplotlib or seaborn.

## Results

- Top 10 Anime by Rating:
    - Example: **Anime 1** (Rating: 9.5)
  
- Top 10 Anime by Popularity (Members):
    - Example: **Anime 2** (Members: 1,200,000)

- Combined Ranking based on Rating and Popularity:
    - Example: **Anime 3** (Weighted Score: 8.9)

## Technologies Used

- **Python**: Core programming language used for data manipulation and analysis.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Numerical computing library.
- **Matplotlib/Seaborn**: (Optional) Libraries for data visualization.

## Future Enhancements

- **Recommendation System**: Build a simple recommendation system based on anime genres and user preferences.
- **Advanced Visualizations**: Create detailed plots to showcase trends in anime ratings, popularity, and genres.
- **Integration with Web Framework**: Display the rankings and analysis in a web interface using Flask or Django.

