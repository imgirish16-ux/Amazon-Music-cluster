# Amazon-Music-cluster
Unsupervised ML project that clusters Amazon Music songs into meaningful sound groups using K-Means, PCA visualization, Silhouette Score, and Davies–Bouldin evaluation on audio features like danceability, energy, and tempo
#  Amazon Music Clustering — Unsupervised Learning Project

This project applies **Unsupervised Machine Learning (K-Means Clustering)** to group songs from Amazon Music into meaningful clusters based on their audio characteristics such as danceability, energy, tempo, valence, and more.

The goal is to automatically discover patterns in how songs *sound* and infer possible musical styles or moods — without using any genre labels.

---

##  Problem Statement

With millions of songs available on streaming platforms, manually categorizing music into genres is inefficient. This project uses clustering techniques to group similar songs based on audio features, enabling:

- Personalized playlist creation
- Music recommendation systems
- Song similarity analysis
- Market segmentation based on listening behavior

---

## Approach

1. Data Cleaning & Feature Selection
2. Feature Scaling using StandardScaler
3. Optimal K selection using Elbow Method & Silhouette Score
4. K-Means Clustering (K = 4)
5. PCA for 2D Visualization
6. Cluster Evaluation using:
   - Silhouette Score
   - Davies–Bouldin Index
7. Cluster Interpretation using feature averages
8. Visualization using scatter plots and heatmaps

---

## Features Used

- danceability
- energy
- loudness
- speechiness
- acousticness
- instrumentalness
- liveness
- valence
- tempo

These features describe the rhythm, intensity, mood, and instrumentation of songs.

---

## Evaluation Metrics

| Metric | Value | Interpretation |
|--------|-------|----------------|
| Silhouette Score | Highest at K=4 | Best cluster separation |
| Davies–Bouldin Index | 1.46 | Good cluster compactness |

---

## Visualizations

- Elbow Method graph
- PCA Cluster Scatter Plot
- Feature Heatmap per Cluster

---

##  Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

---


