# Spotify Music Analytics

## Project Overview
This project explores Spotify track data to understand music popularity, genre performance, track duration, and audio characteristics using Python. The goal is to derive meaningful insights that can support music-related business decisions.

## Business Use Case
Music streaming platforms need to understand which genres and audio characteristics are associated with popular tracks. This analysis explores patterns in track popularity and compares music attributes to identify useful trends.

## Objectives
- Analyze the distribution of track popularity.
- Identify genres with higher average popularity.
- Explore relationships between audio features and popularity.
- Compare explicit and non-explicit tracks.
- Analyze track duration and artist performance.
- Translate analytical findings into business recommendations.

## Dataset
The project uses the Spotify Tracks Dataset obtained from Kaggle.

Dataset source: [Spotify Tracks Dataset on Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)

The dataset contains track information, genre labels, popularity scores, and audio features such as danceability, energy, loudness, valence, and tempo.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data loading and inspection
2. Data cleaning and validation
3. Exploratory Data Analysis (EDA)
4. Business-question analysis
5. Key findings and business recommendations
6. Limitations and future scope

## Key Findings
- Track popularity does not have a strong linear relationship with individual audio features in this dataset.
- Pop-film had the highest average popularity among the genres examined in the top-10 comparison.
- Explicit tracks had a higher average popularity than non-explicit tracks in this dataset; this does not establish causation.
- Tracks between 3 and 5 minutes had the highest average popularity among the duration groups analyzed.
- Popularity varies across genres and artists, suggesting that multiple factors may influence track performance.

## Business Recommendations
- Evaluate genre-level performance using average popularity alongside track counts.
- Avoid using a single audio feature as the sole indicator of track success.
- Consider duration and explicit-content status as descriptive factors, not guarantees of popularity.
- Combine track analytics with streaming, playlist, and release-date data for deeper insights.

## Limitations
- Popularity scores may not represent actual streaming counts.
- The analysis identifies associations and does not establish causation.
- Artist names may contain multiple artists in a single field.
- The dataset represents a particular snapshot and may not reflect current listening trends.

## Future Scope
- Build a machine-learning model to predict track popularity.
- Develop a music recommendation system.
- Create an interactive dashboard using Power BI or Tableau.
- Integrate streaming counts, playlist data, and release dates for deeper analysis.

## Author
**Divya Dande**

[GitHub Profile](https://github.com/Dandedivya)
