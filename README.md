# Ali's Portfolio
# Movie Recommendation System

## Project Description
This project is a **content-based movie recommendation system** designed to suggest similar movies based on a given movie title selected from the data. Using features like movie title, genre, overview, cast, and popularity. The recommendation engine computes similarity scores between movies to find the closest matches. This project demonstrates foundational skills in natural language processing, machine learning, and data engineering/analaysis.

## Dataset
Attained from kaggle (https://www.kaggle.com/datasets/khalidalam980/top-rated-movies-data-set)
The dataset used for this project is stored in the `data` folder as `Movies_cleaned.csv`, which contains information on movies, including columns such as `id`, `title`, `genre_ids`, `overview`, `popularity`, `release_date`, `vote_average`, and `vote_count`.

### Key Columns in the Dataset:
- **id:** Unique identifier for each movie
- **title:** Title of the movie
- **genre_ids:** Genre IDs associated with each movie
- **overview:** Brief synopsis of the movie
- **popularity:** Popularity score of the movie
- **release_date:** Date the movie was released
- **vote_average:** Average rating of the movie
- **vote_count:** Number of votes the movie received

### Tools and Libraries Used
Python: Programming language used for the entire project.
Excel: Used to clean, organize, and preprocess the initial dataset before loading it into Python for further analysis.
Jupyter Notebook: Used to develop and document the project interactively, especially useful for feature engineering and experimentation.
scikit-learn: Used for TF-IDF vectorization and cosine similarity calculations.
NumPy: For matrix handling and efficient numerical operations.
Pandas: Data manipulation and feature engineering.
NLTK (Natural Language Toolkit): Optional, for advanced text preprocessing if required.

