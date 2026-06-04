# AI Movie Recommendation System

## Overview

This project implements a Content-Based Movie Recommendation System using Machine Learning and Natural Language Processing (NLP) techniques.

The system recommends movies similar to a selected movie by analyzing features such as genres, keywords, cast, crew, and movie descriptions. Cosine Similarity is used to identify and rank similar movies.

---

## Dataset

TMDB 5000 Movie Dataset

Files Used:

* tmdb_5000_movies.csv
* tmdb_5000_credits.csv

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* Pickle
* Cosine Similarity

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Text Preprocessing
5. Vectorization using CountVectorizer
6. Cosine Similarity Calculation
7. Movie Recommendation Generation

---

## How It Works

* Movie metadata is collected from the TMDB dataset.
* Important features such as genres, keywords, cast, crew, and overview are combined into a single text feature.
* Text data is vectorized using CountVectorizer.
* Cosine Similarity is calculated between movie vectors.
* The system recommends the most similar movies based on similarity scores.

---

## Example

**Input Movie:** Avatar

**Recommended Movies:**

* Titan A.E.
* Small Soldiers
* Ender's Game
* Alien vs. Predator
* Riddick

---

## Project Structure

AI-Movie-Recommendation-System/

* Movie_Recommender_Training.ipynb
* Movie_Recommender_Testing.ipynb
* movie_list.pkl
* tmdb_5000_movies.csv
* tmdb_5000_credits.csv
* requirements.txt
* README.md

---

## Note

The file `similarity.pkl` is not included in this repository because it exceeds GitHub's file size limit.

To generate it:

1. Open `Movie_Recommender_Training.ipynb`
2. Run all cells
3. `similarity.pkl` will be generated automatically

---

## Author

**Anjali Chauhan**

