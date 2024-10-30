# Ali's Portfolio
# Movie Recommendation System

## Project Description
This project is a **content-based movie recommendation system** designed to suggest similar movies based on a given movie title selected from the data. Using features like movie title, genre, overview, cast, and popularity. The recommendation engine computes similarity scores between movies to find the closest matches. This project demonstrates foundational skills in natural language processing, machine learning, and data engineering/analysis.

## Dataset
Attained from Kaggle (https://www.kaggle.com/datasets/khalidalam980/top-rated-movies-data-set)
The dataset used for this project is stored in the `data` folder as `Movies_cleaned.csv`, which contains information on movies, including columns such as `id`, `title`, `genre_ids`, `overview`, `popularity`, `release_date`, `vote_average`, and `vote_count`.

### Data Cleaning/Preparation
1. Handling Missing Values: Any rows with critical missing information, such as missing titles or overviews, were either filled if possible or removed to maintain data quality.
2. Standardizing Text Data: The overview and genre_ids columns were standardized to remove any inconsistencies in formatting, making them easier to process later in Python.
3. Parsing Dates: The release_date column was converted to a consistent date format to facilitate sorting or filtering by date if needed.
4. Removing Duplicates: Duplicate movie entries were identified and removed to avoid redundant recommendations.
5. Saving the Cleaned Data: The cleaned data was saved in Movies_cleaned.csv, which is used as the primary dataset for this project


### Tools and Libraries Used
1. Python: Programming language used for the entire project.
2. Excel: Organize and preprocess the initial dataset before loading it into Python for further analysis & Cleaning.
3. Jupyter Notebook: This is used to Clean, develop, and document the project interactively. It is especially useful for feature engineering and experimentation.
4. scikit-learn: Used for TF-IDF vectorization and cosine similarity calculations.
5. NumPy: For matrix handling and efficient numerical operations.
6. Pandas: Data manipulation and feature engineering.
7. NLTK (Natural Language Toolkit): Optional, for advanced text preprocessing if required.


### Key Columns in the Dataset:
- **id:** Unique identifier for each movie
- **title:** Title of the movie
- **genre_ids:** Genre IDs associated with each movie
- **overview:** Brief synopsis of the movie
- **popularity:** Popularity score of the movie
- **release_date:** Date the movie was released
- **vote_average:** Average rating of the movie
- **vote_count:** Number of votes the movie received





