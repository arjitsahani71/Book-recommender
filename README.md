📚 Book Recommender System

A Flask-based Book Recommender System that suggests books based on similarity and popularity using machine learning techniques.
The application features a modern dark UI, book cover previews, and an interactive recommendation search.

🚀 Features

Top 50 Popular Books displayed on the home page
Book Recommendation Engine using cosine similarity
Displays book covers, authors, ratings, and votes
Clean, responsive dark-themed UI
Separate pages for Home, Recommend, and Contact
Uses pre-trained ML models (pickle files)
Built with Flask + Python

🛠️ Tech Stack

Backend: Python, Flask
Frontend: HTML, CSS, Bootstrap
Machine Learning:
  Pandas
  NumPy
  Cosine Similarity
Data Storage: Pickle (.pkl) files

Project Structure
Book-recommender/
│
├── app.py
├── popular.pkl
├── pt.pkl
├── books.pkl
├── similarity_score.pkl
│
├── templates/
│   ├── index.html
│   ├── recommend.html
│   └── contact.html
│
└── static/ (optional)

🌟 Future Improvements
  Add star-based rating UI
  Autocomplete search suggestions
  Wishlist / favorites
  User authentication

