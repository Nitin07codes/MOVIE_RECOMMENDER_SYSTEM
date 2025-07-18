# MOVIE_RECOMMENDER_SYSTEM
A content-based Movie Recommendation System built using Python and Machine Learning techniques. This project analyzes movie metadata to recommend similar movies based on a given title.

Features
Recommends movies based on content similarity
Utilizes TF-IDF and cosine similarity for text-based recommendation
Interactive Jupyter Notebook for code execution and results
Clean and well-commented code for learning and customization


Dataset
Uses the TMDB 5000 Movies and Credits dataset from Kaggle:
tmdb_5000_movies.csv
tmdb_5000_credits.csv
You can find the original dataset here: Kaggle - TMDB 5000 Movie Dataset

Tools and Tech used
1.Python
2.Pandas, NumPy
3.Scikit-learn
4.NLTK
5.Pickle for model/data serialization
6.Jupyter Notebook for demonstration

How It Works
Extracts important features like genres, keywords, cast, crew, and overview
Merges all textual information into a single "tags" field
Applies TF-IDF Vectorization to the tags
Calculates cosine similarity between movies
Recommends the most similar movies based on vector distance


Future Improvements
Add collaborative filtering for hybrid recommendations
Build a web UI using Flask or Streamlit
Add poster/image support using TMDB API
