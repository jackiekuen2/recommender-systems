# recommender-systems

## Datasets
- <strong>The Movies Dataset</strong> https://www.kaggle.com/rounakbanik/the-movies-dataset
  - <strong>Content-Based Recommender: </strong> [link](https://github.com/jackiekuen2/recommender-systems/blob/main/Kaggle_The_Movie_Dataset_Content_based_Recommender_in_plot_TFIDF.ipynb)
    - Context: Plot descriptions
    - TF-IDF Vectorizer + Linear Kernel as Cosine Similarity
  - <strong>Content-Based Recommender: </strong> [link](https://github.com/jackiekuen2/recommender-systems/blob/main/Kaggle_The_Movie_Dataset_Content_based_Recommender_in_cast_keywords_director_genres.ipynb)
    - Context: Cast (top 3 actors), Crew (only director), genres, plot keywords
    - Count Vectorizer + Cosine Similarity
  - <strong>Collaborative Filtering & Hybird Recommenders: </strong> [link](https://github.com/jackiekuen2/recommender-systems/blob/main/Kaggle_The_Movie_Dataset_Collaborative_Filtering_and_Hybird_Recommender.ipynb)
    - Credits to: https://www.kaggle.com/rounakbanik/movie-recommender-systems/notebook
    - Context: Cosing Similarities on (tagline + overview) + SVD on user ratings
    - Surprise library: Singular Value Decomposition (SVD)
