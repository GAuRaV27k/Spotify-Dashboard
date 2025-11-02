# 🎵 Spotify Dashboard 🎛️

An interactive data analysis and visualization project exploring Spotify audio features to uncover patterns in **tempo**, **energy**, **danceability**, **valence**, **loudness**, and **track popularity**.

📓 **Live Notebook:** `Spotify_Dashboard.ipynb`  
📂 **Dataset:** `SpotifyFeatures.csv`

---

## 📚 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Dataset](#-dataset)
- [Files Included](#️-files-included)
- [Installation](#️-installation)
- [How to Run](#️-how-to-run)
- [Notebook Walkthrough](#-notebook-walkthrough)
- [Visualizations and Insights](#-visualizations-and-insights)
- [Suggested Improvements](#-suggested-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🚀 Project Overview
This project loads a local **Spotify audio-features CSV**, performs **data cleaning and feature engineering**, and produces an **interactive exploratory dashboard** using Python.

The goal is to explore relationships between musical features (tempo, energy, danceability, valence, loudness, etc.) and target variables such as **popularity** and **genre**.

---

## ✨ Key Features
- 🧹 Data cleaning: duplicate removal and null handling  
- 🔁 Feature transformations (e.g., converting `duration_ms` → `duration_min`)  
- 🔎 Exploratory Data Analysis (EDA)  
- 📈 Visualizations with **Matplotlib**, **Seaborn**, and **Plotly**  
- 🧩 Interactive charts in a Jupyter Notebook environment  

---

## 📂 Dataset
**Filename:** `SpotifyFeatures.csv` (included in repository)

**Important Columns**
- 🎵 `track_name` — Name of the song  
- 👤 `artist_name` — Artist of the track  
- 🏷️ `genre` — Genre classification  
- 🥁 `tempo` — Beats per minute  
- ⚡ `energy` — Intensity or activity level (0–1)  
- 💃 `danceability` — How suitable the track is for dancing (0–1)  
- 😊 `valence` — Musical positiveness (0–1)  
- 🔊 `loudness` — Overall loudness in decibels (dB)  
- ⏱️ `duration_ms` — Track length in milliseconds  
- ⌛ `duration_min` — Derived duration in minutes  

**Notes**
- The dataset should be located in the project root.  
- If any columns differ, update the notebook accordingly.  

---

## 🗂️ Files Included
- `Spotify_Dashboard.ipynb` — Jupyter Notebook with analysis and visualizations  
- `SpotifyFeatures.csv` — Source dataset
- `README.md` — Project documentation  
<img width="1255" height="450" alt="newplot" src="https://github.com/user-attachments/assets/bc52f4a9-4045-4352-b7d7-3a0d5100a4e2" />
<img width="1255" height="450" alt="newplot" src="https://github.com/user-attachments/assets/879ff6da-fa21-4562-aa86-bafaa939b46a" />
<img width="515" height="435" alt="image" src="https://github.com/user-attachments/assets/02993557-b28c-4060-91b9-1291fb83c830" />

---

## ⚙️ Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/GAuRaV27k/Spotify-Dashboard.git

