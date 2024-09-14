# Exploratory Data Analysis - Movie Recommendation

This repository contains an exploratory data analysis (EDA) on a movie recommendation dataset. The objective of this analysis is to gain insights and understanding of the dataset in order to build a functional movie recommender system. The dataset used in this project is a modified version of the MovieLens dataset, which contains millions of 5-star ratings provided by users of the MovieLens movie recommendation service. In addition to the ratings data, the dataset also includes supplementary movie content data obtained from IMDB.

## Objective

The objective of this project is to accurately predict how a user will rate a movie they have not yet seen, based on their historical preferences. The goal is to create a movie recommender system that can provide users with personalized recommendations, thereby enhancing user experience and generating revenue for the platform.

## Dataset Overview

The dataset used in this analysis consists of the following files:

- `genome_scores.csv`: Contains a score mapping the strength between movies and tag-related properties.
- `genome_tags.csv`: Provides user-assigned tags for genome-related scores.
- `imdb_data.csv`: Contains additional movie metadata scraped from IMDB using the links.csv file.
- `links.csv`: Provides a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
- `sample_submission.csv`: A sample of the submission format for the hackathon.
- `tags.csv`: User-assigned tags for the movies within the dataset.
- `test.csv`: The test split of the dataset, containing user and movie IDs with no rating data.
- `train.csv`: The training split of the dataset, containing user and movie IDs with associated rating data.

The dataset includes ratings provided by users for different movies, along with additional movie metadata such as title, cast, director, runtime, budget, and plot keywords obtained from IMDB. The genome scores represent the importance or relevance of specific attributes or characteristics of a movie in determining its overall profile. These scores can be used to identify patterns and similarities between movies, enabling personalized recommendations based on user preferences.

## Key Observations

During the exploratory data analysis, several key observations were made:

1. Ratings Distribution: The majority of movies in the dataset have ratings above average, with the most common ratings being 3.0, 4.0, and 5.0. Users tend to rate movies using integer values rather than float values, indicating a preference for whole number ratings.

2. Most Rated Movies: The top-rated movies in terms of the number of ratings received are "Swimming with Sharks" and "It Could Happen to You." However, it's important to note that high ratings do not necessarily indicate the quality of the movies.

3. Movie Genres: The most common genres among the top-rated movies are drama and comedy, while movies with the IMAX genre receive the least ratings. This suggests that users are more likely to enjoy movies in the drama genre compared to musical movies.

4. Movie Production: There has been a significant increase in movie production after 2000 compared to earlier years. However, the year 2019 appears to be an anomaly with a lower number of movies produced. Further investigation is needed to understand the factors influencing this decline.

5. User Ratings over Time: The year 1995 had the highest user ratings, which can be attributed to the popularity of movies released during that year. Around 18% of the movies in 1995 was rated 5.0.

## Conclusion

This exploratory data analysis provides valuable insights into the movie recommendation dataset. The findings can be used to develop a movie recommender system that takes into account user preferences, movie genres, and historical ratings. By leveraging the dataset's rich information on movie attributes and user ratings, it is possible to create a personalized recommendation algorithm that enhances the user experience and promotes engagement with the movie platform.