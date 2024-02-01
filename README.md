# Movie Recommendation System

## Overview

This repository contains a Movie Recommendation System based on cosine similarity. The system suggests movies similar to a user's preferences by analyzing the cosine similarity between movies.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Algorithm](#algorithm)
5. [Results](#results)

## Introduction

The goal of this project is to provide personalized movie recommendations to users based on their preferences. The recommendation system employs cosine similarity to measure the similarity between movies, allowing it to suggest movies with similar content.

## Dataset

The dataset used for this recommendation system is included in the `data` directory. It consists of information about movies, such as genre, director, and user ratings.

## Dependencies

Ensure you have the following dependencies installed before running the recommendation system:

- Python (>=3.6)
- NumPy
- Pandas
- Scikit-learn
- cosine_similarity
- TfidfVectorizer

## Algorithm
The recommendation system uses cosine similarity to measure the similarity between movies. The cosine similarity score is calculated based on the movie features, such as genre, director, and user ratings. This score is then used to recommend movies with the highest similarity to the user's input.

## Results
The results of the recommendation system, including a list of recommended movies and their similarity scores, are presented in the console output. Users can explore these recommendations to discover movies similar to their preferences.
