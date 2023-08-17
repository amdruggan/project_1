# Data Science Project: Spotify Data Analysis

This repository contains the code and data for a data science project that involves collecting and analyzing data from Spotify using Python and various libraries. The project aims to answer specific questions related to music tracks' characteristics and their relationship with popularity, genre, and other features.

## Project Overview

The primary goal of this project is to analyze the characteristics of the top 1000 songs from the current year (2023) on Spotify. The analysis is performed using Jupyter notebooks and various Python libraries, including pandas, json, requests, numpy, matplotlib, scipy, seaborn, and spotipy. The project is divided into three main sections, each addressing specific research questions.

### Contributors and Research Questions

- **Chelsea**
  - **Q1**: What are the top 10 popular artists at the moment, and is there a relationship between their popularity and the genre of music they produce?
  - **Q2**: How do the energy levels of the top 5 songs compare to the bottom 5 songs? Do energy levels contribute to the popularity of the songs?

- **Cindy**
  - **Q1**: How does the energy of a track relate to its danceability for the top 10 genres?
  - **Q2**: Is there any connection between audio features (speechiness and loudness) of a track and its popularity?

- **Alec**
  - **Q1**: What are the song durations in this dataset, and what type of distribution describes their duration?
  - **Q2**: Do the song lengths correlate with their energy, valence, and danceability?

## Repository Structure

The repository is organized as follows:

- `pull_spotify_data.ipynb`: Jupyter notebook used to collect data from Spotify API and generate CSV files containing track information for the top 1000 songs from 2023.
- `main.ipynb`: Jupyter notebook that performs data analysis and visualization using the collected track information and various Python libraries.
- The other files in the repository are the data files we used at the time of analysis. 

## Installation

To run the notebooks and reproduce the analysis, follow these steps:

1. Clone this repository to your local machine using `git clone <[repository_url](https://github.com/amdruggan/project_1/edit/main/README.md)>`.
2. Create a virtual environment and activate it (recommended but optional).
3. Install the required dependencies.

## Usage

1. Open `pull_spotify_data.ipynb` and execute the notebook to collect the necessary data from the Spotify API and generate CSV files in the `data/` directory.
2. Open `main.ipynb` to explore the data analysis and visualization process for each of the research questions.

## Results

The analysis and findings for each research question are documented in the `main.ipynb` notebook. Visualizations, statistical tests, and interpretations are provided to address the project's objectives.

## Conclusion

This repository showcases the process of collecting, analyzing, and visualizing Spotify data using Python and relevant libraries. The research questions posed by each contributor provide insights into the relationships between music characteristics, genre, and popularity. The notebooks serve as valuable references for future analyses and inquiries related to music data.

For any questions or suggestions, feel free to reach out to the project contributors: Chelsea, Cindy, and Alec.

**Note**: Due to the dynamic nature of the Spotify API and music trends, the results are specific to the data collected during the project's timeframe (2023).

---
*Disclaimer: This project is for educational and exploratory purposes. It is not affiliated with Spotify.*
