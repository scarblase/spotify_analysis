# Spotify Analysis 🎵

Welcome to the **Spotify Analysis** repository! This project dives deep into the top 1000 most-played Spotify tracks of all time, exploring trends, patterns, and insights through data analysis and visualization.

## 🌟 Project Highlights

- Analyze and visualize Spotify's **Top 1000 Tracks** dataset.
- Use **DuckDB** for SQL-style queries on the dataset. (Yes, we tried DuckDB just to see how it works! 😉)
- Beautiful, Spotify-themed visualizations.
- Explore trends in artists, albums, track durations, and popularity.

---

## 📊 Dataset Overview

The dataset contains information on 1000 tracks, with the following attributes:

| Column         | Description                                      |
|----------------|--------------------------------------------------|
| **track_name** | Name of the track.                              |
| **artist**     | Name of the artist.                             |
| **album**      | Album associated with the track.                |
| **release_date** | Track's release date.                         |
| **popularity** | Popularity score (0-100).                       |
| **spotify_url** | Link to the track on Spotify.                  |
| **id**         | Unique Spotify track ID.                        |
| **duration_min** | Track duration in minutes.                    |
| **release_year** | Year of release (derived).                    |
| **release_month** | Month of release (derived).                  |

---

## 🧰 Tools and Technologies

This project leverages the following tools and libraries:

- **DuckDB**: SQL-style queries on DataFrames (because why not try it? 😄).
- **Pandas**: Data wrangling and exploratory analysis.
- **Matplotlib** & **Seaborn**: Stunning visualizations.
- **BeautifulSoup**: Web scraping (initial attempts to fetch data).
- **Python**: The powerhouse behind everything.

---

## 📈 Key Insights and Visualizations

### 1. **Top Artists and Albums**
- Bar charts showing the **Top 10 Artists** and **Top 5 Albums** based on the number of tracks.
- Styled with Spotify's signature **black, green, and white** theme for a clean and modern look.

### 2. **Popularity Trends**
- **Line Plots**:
  - Popularity trends over the years.
  - Monthly popularity patterns.
- **Scatter Plot**:
  - Relationship between track duration and popularity.

### 3. **Distribution Analysis**
- **KDE Plots** to showcase the distribution of:
  - Track popularity.
  - Track durations.

### 4. **Popular Tracks by Artist**
- Extracted the **most popular track** for each artist with a popularity score ≥ 90 using **DuckDB**.

---

## 🎨 Spotify-Themed Styling

- **Color Palette**:
  - Spotify Black: `#121212`
  - Spotify Green: `#1DB954`
  - Spotify Light Grey: `#B3B3B3`
  - Spotify White: `#FFFFFF`
- Fonts and gridlines styled to match Spotify's sleek UI.

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/scarblase/spotify_analysis.git
cd spotify_analysis
```

### 2. Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install pandas duckdb matplotlib seaborn requests beautifulsoup4
```

### 3. Load the Dataset
Ensure the file `spotify_top_1000_tracks.csv` is in the repository's root directory.

### 4. Run the Jupyter Notebook
Launch Jupyter Notebook to explore the analysis:
```bash
jupyter notebook
```

---

## 🌐 References

- **Dataset Source**: [Kaggle - Top 1000 Most Played Spotify Songs of All Time](https://www.kaggle.com/datasets/kunalgp/top-1000-most-played-spotify-songs-of-all-time)
- **Spotify**: [Spotify](https://www.spotify.com)

---

✨ Dive into the dataset and enjoy uncovering the magic of Spotify's top tracks!
