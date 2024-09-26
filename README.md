
# Spotify Data Analysis Project

## Project Overview

This project analyzes a comprehensive dataset of Spotify tracks to provide insights into music trends, track popularity, and other audio features. By leveraging Python libraries, the project explores various relationships within the data, focusing on key track metrics such as duration, popularity, and audio features like tempo and loudness.

### Dataset Description

The project uses two datasets from Kaggle:
1. [Ultimate Spotify Tracks DB](https://www.kaggle.com/datasets/zaheenhamidani/ultimate-spotify-tracks-db)
2. [Spotify Datasets (Artists)](https://www.kaggle.com/datasets/lehaknarnauli/spotify-datasets?select=artists.csv)

Key attributes in the datasets include:
- **Track Name**: The name of the track.
- **Artist Name**: The name of the artist.
- **Album Name**: The album in which the track is featured.
- **Release Date**: Date when the track was released.
- **Duration (ms)**: Duration of the track in milliseconds.
- **Popularity**: Popularity score of the track (0-100).
- **Explicit**: Indicates whether the track contains explicit content.
- **Audio Features**: These include tempo, energy, danceability, loudness, and more.

### Key Data Insights
1. **Null Values Check**: Evaluated missing data within the dataset to ensure data quality.
2. **Track Duration**: Insights into the average duration of tracks.
3. **Track Popularity**: Analysis of track popularity scores and their distribution.
4. **Audio Feature Correlations**: Explored relationships between various audio features like loudness, tempo, and danceability.

### Visualizations
1. **Track Popularity Distribution (Histogram)**: Displays the distribution of popularity scores across all tracks.
2. **Track Duration by Release Year (Line Chart)**: Shows the trend in average track duration over the years.
3. **Top 10 Artists by Track Count (Bar Chart)**: Visualizes the artists with the most tracks in the dataset.
4. **Correlation Heatmap (Seaborn Heatmap)**: Displays the correlations between different audio features like danceability, energy, and loudness.

### Technology Stack
- **Python**: For data analysis and processing.
- **Pandas & NumPy**: For data manipulation and statistical analysis.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For interactive data exploration.

### How to Use the Project
1. Download the datasets from the links provided.
2. Ensure the datasets are placed in the correct directory.
3. Run the Python code to perform the analysis.
4. Visualize trends and insights using the provided visualizations.

### Conclusion
This Spotify Data Analysis project provides a detailed look into Spotify's music trends, analyzing key metrics like popularity and audio features. The visualizations offer a clear understanding of the relationships between various attributes, helping to identify trends in music data.

