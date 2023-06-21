# movie-recommender-system

## View website: http://localhost:8501/

<img src="https://github.com/hemantbuchade/movie-recommender-system/blob/main/movies_app.png" alt="Movies" width="100%">

## Problem Statement:
- The goal of this project is to develop a movie recommender system using a dataset of movies. The challenge is to provide accurate and relevant movie recommendations to users based on their input movie.

## Action of Work:

- Data Preparation: The code imports the movie dataset and performs necessary data cleaning and preprocessing steps. It merges the movies and credits data, selects relevant columns, handles missing values, and transforms certain columns for further analysis.

- Feature Extraction: The code extracts key features such as genres, keywords, cast, and crew from the dataset. It applies custom functions to convert these features into usable formats, such as lists of names or strings.

- Tag Generation: The code combines the extracted features into a new 'tags' column, which represents a combination of movie information including genres, keywords, cast, and crew.

- Vectorization: The code utilizes the CountVectorizer class to convert the 'tags' column into a matrix of token counts. This process transforms the textual data into a numerical representation that can be used for calculating similarity between movies.

- Similarity Calculation: The code calculates the cosine similarity matrix using the cosine_similarity function. This matrix captures the pairwise cosine similarities between movies based on their feature vectors.

- Recommendation: The code defines the 'recommend' function, which takes a movie title as input. It retrieves the index of the movie, calculates the cosine similarity distances, and selects the top 5 most similar movies. Finally, it prints the titles of these recommended movies.

## Result:
- The developed movie recommender system successfully provides recommendations for similar movies based on the input movie title. By utilizing cosine similarity and considering various movie features, the system suggests movies that are likely to be of interest to users who enjoyed the input movie.

## Conclusion:
- In conclusion, the movie recommender system implemented in this project effectively leverages movie features and cosine similarity to provide accurate recommendations. By considering genres, keywords, cast, and crew information, the system captures the essence of movies and finds similar movies that align with users' preferences. The system can be further enhanced by incorporating additional features and refining the recommendation algorithm, ultimately improving the overall user experience in discovering new movies.


Download similarity.pkl:
[similarity.pkl](https://drive.google.com/uc?export=download&id=1UATeXWK0GXNzYyvpEdPIlAyGWHHvNFKF)

