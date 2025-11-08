# MovieRanker-Flask-SQLAlchemy-TMDb

**My Top 10 Movies** is a small Flask web app that lets you curate a personal movie leaderboard. 
Search titles using the **TMDb API**, add them to your library, then assign a **rating** and **review**. The app automatically computes a 
Top-10 ranking based on your ratings and displays posters, years, and overviews.

This project demonstrates:
- **Flask** routing + **WTForms** for input validation
- **SQLAlchemy** ORM models and CRUD over **SQLite**
- Calling a third-party REST API (TMDb) and mapping responses to models
- Clean UI templates with Jinja2 and Bootstrap
- Simple ranking logic derived from stored ratings

Perfect as a learning project to practice API consumption, database CRUD, and form handling in a real Flask application.



## 📂 Project Structure


├── main.py
├── movie.db
├── static/
│ └── style.css
├── templates/
│ ├── index.html
│ ├── edit.html
│ └── add.html
└── README.md




