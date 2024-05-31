## About

This project is part of the Certificate in Advanced Studies in Applied Data Science program at the University of Bern, Switzerland. It was completed by Avisek Regmi, a student enrolled in the program.

## Student Information

- **Name:** Avisek Regmi
- **Program:** Certificate in Advanced Studies in Applied Data Science
- **University:** University of Bern
- **Address:** Hochschulstrasse 4, Bern, Switzerland


# Reel Insights: A Comprehensive Analysis of Movie Recommendation Systems 


![Recommendation System Image](https://recostream.com/cms-asset-100399303/rekomendacje+netflixa.png-1024.jpg)

Welcome to the Movie Recommendation System project! This repository contains the code and resources for building a movie recommendation system using three distinct approaches: Content-Based Filtering, Collaborative Filtering, and Hybrid Recommendation System.

## Overview

This project leverages comprehensive datasets sourced from MovieLens and TMDB platforms to develop robust recommendation algorithms. By combining user ratings, movie metadata, and machine learning techniques, the system aims to provide personalized movie recommendations tailored to individual preferences.

## Data Collection

### MovieLens Dataset

The primary dataset was obtained from the GroupLens website, a well-known repository for movie ratings and metadata (MovieLens). The MovieLens Full Dataset, consisting of 26 million ratings from 270,000 users across 45,000 movies, served as a pivotal resource. The `links.csv` file within this dataset provided essential TMDB and IMDB IDs for all listed movies, facilitating seamless integration with supplementary data sources.

### TMDB API Integration

To enrich the MovieLens data with richer metadata, an API Key was obtained from TMDB. This granted access to detailed information through three critical endpoints: movie details, cast and crew information, and plot keywords. Each endpoint provided unique insights into various facets of the 45,000 movies, necessitating a systematic approach to data extraction.

### Data Scraping and Processing

Given the scope of the data required, three distinct scrapers were developed to interface with each TMDB endpoint. These scrapers methodically requested and retrieved data for all listed movies. However, TMDB’s API imposes a rate limit of 40 requests every 10 seconds, requiring a strategic approach to avoid exceeding these constraints. As a result, the complete data extraction process spanned an entire day.

Upon retrieval, the data was initially in stringified JSON format. This raw format required substantial processing to render it usable for analysis. Using Python’s Pandas library, the JSON data was meticulously converted into structured CSV files, ensuring that the dataset was not only comprehensive but also readily accessible for subsequent exploratory and predictive analyses.

## Recommendation Systems

### Content-Based Filtering

The Content-Based Filtering system recommends movies based on similarities in movie attributes such as genre, director, cast, and plot keywords. By analyzing the content of previously rated movies, this approach identifies patterns and suggests similar movies that match the user's preferences.

### Collaborative Filtering

Collaborative Filtering recommends movies by analyzing user behavior and preferences. It identifies users with similar tastes and recommends movies liked by those users but not yet seen by the target user. This approach effectively captures user preferences and provides personalized recommendations.

### Hybrid Recommendation System

The Hybrid Recommendation System combines the strengths of both Content-Based Filtering and Collaborative Filtering approaches to deliver more accurate and diverse recommendations. By leveraging the complementary nature of these methods, the hybrid system overcomes limitations inherent in individual approaches and provides enhanced recommendation quality.

## Conclusion

This project demonstrates the power of leveraging comprehensive datasets and advanced recommendation algorithms to deliver personalized movie recommendations. By integrating data from multiple sources and employing sophisticated techniques, the system enhances user experience and facilitates exploration of the vast cinematic landscape.

Feel free to explore the code and resources provided in this repository to learn more about the movie recommendation system and its implementation details. Happy movie watching! 🎬🍿

# Thank You

Thank you for taking the time to explore this project! If you have any questions or feedback, feel free to reach out. Your interest is greatly appreciated.

Happy exploring! 🚀



