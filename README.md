# Movie Recommendation System

This is a **Content-Based Movie Recommendation System** built with **Streamlit**. It suggests similar movies based on the movie selected by the user, showing their posters using the TMDB API.

✅ [Live Demo](https://movie-recommender-app-yawzdd76r54lwybv3hhjjp.streamlit.app/)

---

## Features

- Recommends 7 similar movies based on content similarity
- Displays movie posters fetched from [TMDb](https://www.themoviedb.org/)
- Simple and clean user interface using Streamlit
- Cosine similarity used to compute movie similarity
- Deployed on Streamlit Cloud 🚀

---

## Technologies Used

- Python 🐍
- Pandas
- Scikit-learn
- Streamlit (web app framework)
- TMDB API (for movie poster images)
- Hugging Face Hub (to host large `.pkl` file)

---

## Files & Structure

```bash
 movie-recommender-app/
├── moviesweb.py               # Main Streamlit app
├── movies_dataframe.pkl       # Contains movie metadata (title, id, etc.)
├── requirements.txt           # List of required Python libraries
└── README.md              # This file!

Author:
Name: Sunil Limbu
