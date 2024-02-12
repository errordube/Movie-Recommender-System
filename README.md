# Movie-Recommender-System 
## A content based movie recommender system using cosine similarity

# Dataset : 
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data?select=tmdb_5000_movies.csv

## Inspiration
The idea for this project sparked from my personal experiences of spending too much time deciding what movie to watch next. I was fascinated by how platforms like Netflix and Amazon Prime suggest movies based on what I've watched before. I wanted to dive deeper into how these recommendations are made and explore the technology behind them. This curiosity led me to the concept of content-based filtering and the use of cosine similarity to measure similarities between movies.

## What it does
This Content Based Movie Recommender System takes a movie that a user likes and analyzes its features such as genres, descriptions, and key metadata. It then compares these features with those of other movies in the TMDB dataset using cosine similarity. The system ranks all movies based on their similarity scores and suggests the top matches to the user, essentially providing a personalized movie discovery experience and returns the top 5 movies. 

## How we built it
We started by exploring the TMDB movie metadata dataset from Kaggle, understanding its structure, and preprocessing the data to make it suitable for our model. We focused on extracting relevant features that could contribute to the movie's content profile, such as genres, tags, and overview descriptions.

Using Python and libraries like Pandas for data manipulation, Scikit-learn for building the cosine similarity matrix we built the core recommendation engine. The system computes the cosine similarity between the feature vectors of movies and suggests the ones with the highest similarity scores.

## Challenges we ran into
One of the main challenges was dealing with sparse and high-dimensional data, which made the similarity computation complex and time-consuming. We also faced difficulties in preprocessing the data, especially in parsing and extracting meaningful features from the textual data in movie descriptions and tags.

Another challenge was optimizing the recommendation engine to provide relevant and diverse suggestions, avoiding the common pitfall of recommending popular movies too frequently.

## Accomplishments that we're proud of
Successfully building a functional movie recommender system from scratch was a significant achievement for us. We managed to overcome the challenges of data preprocessing and similarity computation, resulting in a system that can make meaningful recommendations based on movie content.

We're also proud of the user-friendly interface we created, which makes it easy for users to interact with the system and discover new movies tailored to their tastes.

## What we learned
Throughout this project, we gained a deeper understanding of content-based filtering mechanisms and the importance of feature selection and preprocessing in building effective recommender systems. We also improved our skills in Python, data manipulation and vectorization.

## What's next for Content Based Movie Recommender System
Looking ahead, we plan to enhance the recommender system by incorporating more complex features such as user ratings, and possibly integrating collaborative filtering techniques to combine the strengths of content-based and collaborative recommendations. We also aim to improve the system's scalability and performance to handle larger datasets and provide faster, more accurate recommendations.


