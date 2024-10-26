# Movie-Recommendations-System

Project Overview
This project provides a content-based recommendation system for movies using NLP techniques. It analyzes movie metadata (genres, keywords, cast, crew, and overviews) to find and recommend similar movies based on cosine similarity.

## Key Features
* Content-Based Filtering: Generates recommendations based on the characteristics of the chosen movie.
* NLP for Text Processing: Uses text preprocessing, tokenization, and stemming to clean and optimize the metadata.
* Cosine Similarity: Calculates similarity between movies using TfidfVectorizer and cosine * similarity to find the most relevant recommendations.
Interactive Interface: Allows users to input a movie title and receive similar movie recommendations.


## Dataset
This project uses the TMDb 5000 Movie Dataset from Kaggle. The dataset includes movie titles, genres, keywords, cast, crew, and overviews.


## Usage
1. Run the Code: Launch the Jupyter notebook and run all cells.
2. Input Movie: Enter a movie title in the provided input field, and the system will output the top 5 recommended movies based on similarity.


##Implementation Details

* Data Preprocessing: Data cleaning is done to remove null and duplicate values. Features such as genres, keywords, cast, crew, and overview are extracted, tokenized, and stemmed for optimal text processing.
* Feature Engineering: Features are combined into a single tags column, which provides a unified description of each movie.
* TF-IDF Vectorization: The tags are vectorized using TfidfVectorizer with stop words removed to reduce noise.
* Cosine Similarity: Measures the similarity between movie tags to rank and recommend movies.


## Contributing
Feel free to fork this project, make improvements, and submit a pull request!
