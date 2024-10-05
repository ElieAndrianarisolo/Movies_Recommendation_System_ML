# Movie Recommendation System using Machine Learning

## Overview

This project is a movie recommendation system that utilizes machine learning to suggest movies based on user input. It is built using a **content-based filtering** technique, where movies are recommended based on their similarity to a selected movie. The model compares movies based on specific features such as **genres** and **overviews**.

## Features

- **Data Preprocessing**: The dataset is preprocessed by combining relevant features like `genre` and `overview` into a single column called `tags` to simplify the recommendation process.
- **Text Vectorization**: The `tags` are vectorized using **CountVectorizer**, which converts the text into numerical vectors.
- **Similarity Calculation**: The system calculates the **cosine similarity** between movies based on their vectorized tags.
- **Recommendation System**: Once a movie is selected, the system recommends the top 5 most similar movies using the cosine similarity scores.


