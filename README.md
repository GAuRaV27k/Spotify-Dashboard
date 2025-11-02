🎧 Spotify Data Dashboard – Data Analyst Project
📊 Project Overview

This project explores and visualizes Spotify music data using Python to uncover patterns and insights about songs, artists, and musical characteristics.
The goal was to create an interactive data dashboard for trend analysis, correlation study, and popularity exploration — simulating a real-world Data Analyst internship project.

🧠 Objectives

Analyze the relationship between audio features like energy, danceability, valence, and tempo.

Identify the most popular artists and genres.

Visualize how different attributes affect song popularity.

Build a clean and interactive dashboard using Plotly, Seaborn, and Matplotlib.

🗂️ Dataset

File: SpotifyFeatures.csv

Contains metadata and musical features of tracks available on Spotify.

Columns include:
genre, artist_name, track_name, popularity, danceability, energy, valence, tempo, loudness, acousticness, instrumentalness, etc.

🧩 Key Steps
1. Data Cleaning & Preparation

Handled missing values and unnecessary columns.

Converted duration from milliseconds to minutes.

Ensured correct data types for analysis.

2. Exploratory Data Analysis (EDA)

Distribution of song popularity.

Top 10 artists by number of songs.

Correlation between audio features.

Tempo vs Energy relationship with popularity.

3. Visualization Dashboard

Created clear and meaningful visuals:

📈 Popularity Distribution Histogram

🎤 Top 10 Artists Bar Chart

🎚️ Correlation Heatmap (Danceability, Energy, Valence, Tempo, Popularity)

🎵 Interactive Scatter Plot (Tempo vs Energy vs Popularity)

🧰 Tools & Libraries Used

Python

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – static visualizations

Plotly Express – interactive visualizations

📍 Key Insights

Most songs cluster around medium popularity (40–60).

Strong correlation between danceability and valence.

Artists like Giuseppe Verdi and Giacomo Puccini dominate in terms of track count.

High energy and tempo don’t always guarantee popularity — emotional tone (valence) also matters.

🚀 Future Improvements

Add time-based trends (if release year data available).

Create a genre-based comparison dashboard.

Deploy interactive dashboard using Streamlit or Power BI.

<img width="1255" height="450" alt="newplot" src="https://github.com/user-attachments/assets/a3e90d49-4b37-4aac-868a-5ce136040012" />
<img width="1255" height="450" alt="1newplot" src="https://github.com/user-attachments/assets/aef6be40-fcdf-472b-ac8c-6358389bd766" />

<img width="515" height="435" alt="image" src="https://github.com/user-attachments/assets/4b2413e1-7cbf-400b-8351-5bf43da89d5d" />

