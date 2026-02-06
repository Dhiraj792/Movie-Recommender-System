🎬 Movie Recommender System

A Movie Recommender System built using Python and Streamlit that suggests movies similar to the one selected by the user. The system uses a similarity model to recommend movies and fetches posters using the TMDB API.

📌 Project Overview

This project recommends movies based on similarity between movies. When a user selects a movie, the system suggests 5 similar movies along with their posters.

The recommendation model is built using movie metadata and similarity calculations.

🚀 Features

Movie recommendation based on similarity

Interactive web interface using Streamlit

Movie poster fetching via TMDB API

Fast recommendation using precomputed similarity matrix

Simple and user-friendly UI

🛠 Technologies Used

Python

Streamlit

Pandas

NumPy

Requests

Pickle

TMDB API

📂 Project Structure
```text
Movie-Recommender-System/
│
├── app.py                     # Streamlit app
├── movies_dict.pkl            # Movies dataset
├── similarity.pkl             # Similarity matrix
├── Movie_Reco_system.ipynb    # Model building notebook
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system

2. Create Virtual Environment (Optional)
python -m venv venv
venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Run Application
streamlit run app.py

▶️ Usage

Launch the app.

Select a movie from dropdown.

Click Recommend.

View recommended movies with posters.

🔑 API Requirement

This project uses TMDB API to fetch movie posters.

You need:

A TMDB API key

Replace API key in app.py if needed.

📈 Future Improvements

Add movie search bar

User rating-based recommendations

Deploy online

Add genres & filters

Add user login & history
