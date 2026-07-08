# Amazon Music Clustering using Machine Learning

## Project Overview

The **Amazon Music Clustering** project is designed to automatically group songs with similar audio characteristics using **Unsupervised Machine Learning (K-Means Clustering)**.

Instead of relying on predefined genres, the model analyzes audio features to discover hidden patterns and create meaningful music clusters.

The project helps users, music streaming platforms, and analysts understand song characteristics, improve recommendation systems, and visualize music similarities through an interactive Streamlit dashboard.

### The project enables stakeholders to monitor:

- Music Cluster Profiles
- Song Similarity Analysis
- Audio Feature Comparison
- Cluster Visualization
- Music Recommendation Insights
- Feature Engineering Analysis
- Interactive Cluster Exploration
- Machine Learning-Based Music Segmentation

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Cleaning & Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| K-Means | Clustering Algorithm |
| PCA | Dimensionality Reduction |
| Streamlit | Interactive Dashboard |
| Jupyter Notebook | Model Development |

# Dataset Information

**Dataset Name:** Amazon Music Dataset

**Learning Type:** Unsupervised Machine Learning

# Audio Features Used

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration (ms)

# Feature Engineering

- Missing Value Handling
- Duplicate Removal
- Feature Selection
- Data Normalization
- Feature Scaling
- PCA Transformation
- Cluster Label Assignment

# Machine Learning Workflow

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Selection
- Data Preprocessing
- Feature Scaling
- Elbow Method
- K-Means Clustering
- Cluster Evaluation
- PCA Visualization
- Streamlit Deployment

# Application Modules

## Home Module

- Project Overview
- Music Clustering Description
- Workflow
- Dataset Information
- Audio Features

## Saved Analysis Portfolio

- Feature Distribution Analysis
- Elbow Method
- PCA Scatter Plot
- Combined Music DNA Radar Chart
- Feature Intensity Heatmap
- Danceability vs Acousticness Comparison

## Live Cluster Explorer

- Cluster Selection
- Music DNA Radar
- Cluster Statistics
- Sample Songs
- Artist Search
- Genre Analysis

# Key Analysis

- Data Cleaning
- Exploratory Data Analysis
- Missing Value Handling
- Duplicate Removal
- Feature Scaling
- Audio Feature Analysis
- K-Means Clustering
- Cluster Profiling
- PCA Visualization

# Cluster Summary

## Cluster 0 – Classical Soundscapes

- High Acousticness
- Low Energy
- Instrumental Music
- Calm and Soft Songs

## Cluster 1 – Commercial Pop

- High Danceability
- High Energy
- Loud Production
- Radio-Friendly Songs

## Cluster 2 – Spoken Word / Rap

- Highest Speechiness
- High Liveness
- Voice-Centric Tracks
- Rap and Podcast Style

## Cluster 3 – Melodic Grooves

- High Valence
- High Danceability
- Happy Songs
- Energetic Music

# Business Use Cases

- Music Recommendation System
- Playlist Generation
- Artist Analysis
- Music Similarity Detection
- Streaming Analytics
- Listener Segmentation
- Market Research
- Audio Feature Analytics

# Cluster Evaluation Metrics

- Elbow Method
- Inertia
- Silhouette Score
- Davies-Bouldin Index
- PCA Visualization
- Cluster Interpretation

# Visualizations

- Feature Distribution
- Elbow Method Plot
- PCA Scatter Plot
- Combined Music DNA Radar Chart
- Individual Cluster Radar Charts
- Feature Intensity Heatmap
- Danceability vs Acousticness Comparison

# Project Structure

```text
Amazon-Music-Clustering/
│
├── AMC_final.ipynb
├── AMC_StreamlitFinal.py
├── single_genre_artists.csv
├── cleaned_clustering_features.csv
├── final_clustered_music_dataset.csv
│
├── kmeans_elbow_method_plot.png
├── music_pca_dataframe_scatter.png
├── simple_music_radar_chart.png
├── music_radar_cluster_0.png
├── music_radar_cluster_1.png
├── music_radar_cluster_2.png
├── music_radar_cluster_3.png
├── Feature Intensity Heatmap per Cluster.png
├── Danceability vs Acousticness across Clusters.png
├── feature_distributions.png
│
└── README.md
```

# Future Enhancements

- Spotify API Integration
- Music Recommendation Engine
- Automatic Genre Prediction
- Deep Learning Models
- Explainable AI
- Cloud Deployment
- Interactive Analytics Dashboard
- Mobile-Friendly Application

# Conclusion

The **Amazon Music Clustering** project demonstrates how **Unsupervised Machine Learning** can automatically discover meaningful music patterns using audio features.

By combining **Exploratory Data Analysis (EDA), Feature Engineering, K-Means Clustering, PCA Visualization, and an Interactive Streamlit Dashboard**, the project provides valuable insights for music recommendation systems, playlist generation, music analytics, and streaming platforms.
