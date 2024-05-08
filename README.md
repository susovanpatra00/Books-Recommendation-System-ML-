# Book Recommendation System using ML

## Types of Recommendation System

### 1. Content-Based Recommendation System:
   - **Description:** Content-based recommendation systems recommend items similar to those the user has liked or interacted with in the past. The recommendations are based on the attributes or features of the items themselves.
   - **Example:** Consider a movie streaming platform where users have rated movies they've watched. A content-based recommendation system can recommend similar movies based on attributes such as genre, actors, directors, and plot keywords.

### 2. Collaborative Filtering Recommendation System:
   - **Description:** Collaborative filtering recommendation systems make recommendations by analyzing the interactions and preferences of multiple users. It identifies patterns and similarities among users or items to generate recommendations.
   - **Example:** In a collaborative filtering system for e-commerce, if User A and User B have similar purchase histories and preferences, the system can recommend products to User A that User B has previously purchased and liked.

### 3. Hybrid Recommendation System:
   - **Description:** Hybrid recommendation systems combine multiple recommendation techniques, such as content-based filtering, collaborative filtering, and other approaches, to provide more accurate and diverse recommendations.
   - **Example:** A music streaming service may use a hybrid recommendation system that combines collaborative filtering (based on user listening history and preferences) with content-based filtering (based on music genre, artist similarity, etc.).

In our project, we will use the Collaborative Filtering method.

## Features

- Implements a book recommendation system using collaborative filtering.
- Reads data from CSV files containing information about books, users, and book ratings.
- Preprocesses the data by filtering out users and books with insufficient data.
- Constructs a pivot table to detect similar interests among users.
- Trains a k-nearest neighbors (KNN) model using the cosine similarity metric.
- Recommends similar books based on a given book title.
- Uses Streamlit for building the user interface.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn
- streamlit

## How to Run

```bash
   streamlit run app.py
```
