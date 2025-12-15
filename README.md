Book Recommender System

A Python-powered book recommendation web application that suggests books based on a user’s preferences. The system uses precomputed similarity scores and book metadata to provide relevant recommendations through a web interface.

Try the deployed version here:
🔗 https://recommend-me-books.onrender.com/




Project Overview

This project builds a book recommendation system that helps users discover books they might like. It uses preprocessed book data and similarity scores to suggest titles that are most relevant based on an input book.

Key components include:

A dataset of books and metadata

Precomputed similarity scores (similarity_scores.pkl)

A Flask web app (app.py)

HTML templates for the user front-end

Pickle files that store the model resources (books.pkl, popular.pkl, pt.pkl)




🛠️ Installation & Setup -->

1. Clone the repository

   git clone https://github.com/ARYANGAUATM001/book_recommender.git
   
   cd book_recommender

2. Install dependencies

   Create and activate a Python virtual environment

   python -m venv venv
   
   source venv/bin/activate

   pip install -r requirements.txt


3. ▶️ Run the App

Start the Flask application:

   python app.py
