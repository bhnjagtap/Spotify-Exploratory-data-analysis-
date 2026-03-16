# Spotify Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Spotify music dataset to understand how different audio features behave across music genres.

The objective of this project is to explore relationships between audio characteristics such as **acousticness and energy**, identify patterns within genres, and gain insights that can support further analysis or machine learning tasks.

---

## Dataset

The dataset contains Spotify track information including several audio features extracted from songs.

Some of the key features used in this analysis include:

- Track Genre
- Acousticness
- Energy
- Other audio characteristics

These features help describe the musical properties of each track.

---

## Project Goals

The main goals of this project are:

- Understand the distribution of audio features
- Identify relationships between different musical attributes
- Explore how genres differ based on audio characteristics
- Visualize patterns and correlations within the dataset

---

## Exploratory Data Analysis

The analysis focuses on:

### 1. Feature Distribution
Understanding how audio features like **acousticness and energy** are distributed across tracks.

### 2. Feature Relationships
Analyzing how two variables interact with each other, particularly:

- Acousticness vs Energy

### 3. Genre-Based Patterns
Examining how different genres cluster based on their audio characteristics.

---

## Key Insights

- There is a noticeable **negative relationship between acousticness and energy**.
- Highly acoustic tracks generally show lower energy levels.
- Different genres show different clustering patterns when visualized across these features.

These insights demonstrate how EDA helps uncover patterns before building predictive models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

spotify-eda/

│
├── data/
│ └── spotify_dataset.csv
│
├── notebooks/
│ └── eda_analysis.ipynb
│
├── visuals/
│ └── eda_visualization.png
│
└── README.md


---

## Visualization Example

The visualization below shows the relationship between **acousticness and energy** along with the distribution of these features across genres.

---

## Future Improvements

- Perform correlation analysis across all audio features
- Apply clustering techniques to identify song groups
- Build a genre classification model

---

## Author

Bhargav Jagtap
