# Recommendation-Systems  
(following DataCamp's article: [Recommender Systems in Python](https://www.datacamp.com/tutorial/recommender-systems-python?utm_adgroupid=157156376311&utm_keyword=&utm_matchtype=&utm_network=s&utm_adpostion=&utm_targetid=dsa-2218886984100&utm_loc_interest_ms=&utm_loc_physical_ms=9073639&utm_content=&gad_source=2))

## About the Dataset

The dataset files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. It includes various feature points such as cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts, and vote averages.

These feature points can be used to train machine learning models for both **content-based** and **collaborative filtering** recommendation systems.

## Dataset Files

The dataset consists of the following files:

- **movies_metadata.csv**: Contains information on ~45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, genre, revenue, release dates, languages, production countries, and companies.
  
- **keywords.csv**: Contains the movie plot keywords for the MovieLens movies. Available in the form of a stringified JSON Object.

- **credits.csv**: Consists of cast and crew information for all the movies. Available in the form of a stringified JSON Object.

- **links.csv**: Contains the TMDB and IMDB IDs of all the movies featured in the Full MovieLens dataset.

- **links_small.csv**: Contains the TMDB and IMDB IDs of a small subset of 9,000 movies from the Full Dataset.

- **ratings_small.csv**: A subset of 100,000 ratings from 700 users on 9,000 movies.

## Full MovieLens Dataset

The Full MovieLens Dataset comprises:
- 26 million ratings
- 750,000 tag applications
- 270,000 users
- 45,000 movies

The full dataset can be accessed from the official [GroupLens website](https://grouplens.org/datasets/movielens/latest).

## Subset Dataset

The subset dataset used in today's tutorial can be downloaded from [Kaggle](https://www.kaggle.com/rounakbanik/the-movies-dataset/data).
