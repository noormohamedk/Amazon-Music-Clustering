Project Overview

The Amazon Music Clustering project is designed to automatically group songs with similar audio characteristics using Unsupervised Machine Learning (K-Means Clustering). Instead of relying on predefined genres, the model analyzes audio features to discover hidden patterns and create meaningful music clusters.

The project helps users, music streaming platforms, and analysts understand the characteristics of songs, improve recommendation systems, and visualize music similarities through an interactive Streamlit dashboard.

The project enables stakeholders to monitor:

Music Cluster Profiles
Song Similarity Analysis
Audio Feature Comparison
Cluster Visualization
Music Recommendation Insights
Feature Engineering Analysis
Interactive Cluster Exploration
Machine Learning-Based Music Segmentation
Technologies Used
Technology	Purpose
Python	Programming Language
Pandas	Data Cleaning & Analysis
NumPy	Numerical Computing
Matplotlib	Data Visualization
Seaborn	Statistical Visualization
Scikit-learn	Machine Learning Model Development
K-Means	Unsupervised Clustering Algorithm
PCA	Dimensionality Reduction & Visualization
Streamlit	Interactive Dashboard
Jupyter Notebook	Data Analysis & Model Development
Dataset Information

Dataset Name: Amazon Music Dataset

Target: Unsupervised Learning (No Target Variable)

Audio Features Used
Danceability
Energy
Loudness
Speechiness
Acousticness
Instrumentalness
Liveness
Valence
Tempo
Duration (ms)
Feature Engineering
Missing Value Handling
Duplicate Removal
Feature Selection
Data Normalization
Min-Max Scaling
Feature Standardization
PCA Transformation
Cluster Label Assignment
Machine Learning Workflow
Data Collection
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Selection
Data Preprocessing
Feature Scaling
Elbow Method
K-Means Clustering
Cluster Evaluation
PCA Visualization
Interactive Dashboard Deployment
Application Modules
Home Module
Project Overview
Music Clustering Description
Machine Learning Workflow
Dataset Information
Feature Description
Saved Analysis Portfolio
Feature Distribution Analysis
Elbow Method Visualization
PCA Cluster Visualization
Combined Music DNA Radar Chart
Feature Intensity Heatmap
Danceability vs Acousticness Comparison
Live Cluster Explorer
Cluster Selection
Music DNA Radar Chart
Cluster Statistics
Sample Song Explorer
Artist Search
Genre Analysis
Cluster-wise Song Information
Key Analysis
Data Cleaning
Exploratory Data Analysis
Missing Value Handling
Duplicate Removal
Feature Scaling
Audio Feature Analysis
K-Means Clustering
Cluster Profiling
PCA Visualization
Cluster Interpretation
Cluster Summary
Cluster 0 – Classical Soundscapes
High Acousticness
Low Energy
Instrumental Music
Soft and Calm Songs
Cluster 1 – Commercial Pop
High Danceability
High Energy
Loud Production
Modern Pop Tracks
Cluster 2 – Spoken Word / Rap
Highest Speechiness
High Liveness
Voice-Centric Music
Rap and Podcast Style Songs
Cluster 3 – Melodic Grooves
High Valence
High Danceability
Energetic Music
Happy and Upbeat Songs
Business Use Cases
Music Recommendation Systems
Playlist Generation
Music Similarity Analysis
Streaming Platform Analytics
Artist Performance Analysis
Listener Preference Segmentation
Music Market Research
Audio Feature Analytics
Cluster Evaluation Metrics
Elbow Method (Optimal K Selection)
Inertia
Silhouette Score
Davies-Bouldin Index
PCA Visualization
Cluster Feature Interpretation
Visualizations Included
Feature Distribution Plots
Elbow Method Plot
PCA Scatter Plot
Combined Music DNA Radar Chart
Individual Cluster Radar Charts
Feature Intensity Heatmap
Danceability vs Acousticness Comparison
Project Structure
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
Future Enhancements
Hybrid Recommendation System
Spotify API Integration
Real-Time Music Classification
Deep Learning-Based Music Embeddings
Automatic Genre Prediction
Personalized Playlist Generator
Cloud Deployment
Explainable AI for Cluster Interpretation
Interactive Music Analytics Dashboard
Mobile-Friendly Streamlit Application
Conclusion

The Amazon Music Clustering project demonstrates how Unsupervised Machine Learning can automatically discover meaningful patterns in music using audio features. By combining Exploratory Data Analysis, Feature Engineering, K-Means Clustering, PCA Visualization, and an interactive Streamlit Dashboard, the project provides valuable insights into song characteristics and cluster behavior. This solution can support music recommendation systems, playlist generation, content analysis, and data-driven decision-making for streaming platforms and music analysts.
