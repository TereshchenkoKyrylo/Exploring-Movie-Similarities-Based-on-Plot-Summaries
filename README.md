# Exploring Movie Similarities Based on Plot Summaries

**Status: Completed**

## Overview

This repository contains an analysis of movie similarities based on plot summaries. The goal is to explore and visualize how movies relate to each other based on their plot content. 
The project includes a detailed examination of textual similarity and clustering, culminating in an interactive panel for user exploration.

## Introduction

This project aims to uncover similarities between movies using their plot summaries. 
By leveraging text analysis techniques such as tokenization, stemming, and TF-IDF vectorization, the analysis clusters movies based on their narrative content.
A hierarchical clustering approach is used to create a dendrogram that visually represents the similarity between movies.

## Data Source

The data for this analysis includes movie plot summaries sourced from IMDb and Wikipedia. The dataset consists of movie titles and their respective plot summaries.

## Analysis

### 1. Text Preprocessing
- **Tokenization:** The plot summaries are tokenized into words and sentences.
- **Filtering:** Non-alphabetic tokens are removed to focus on meaningful words.
- **Stemming:** Words are reduced to their root forms to standardize the data.

### 2. Feature Extraction
- **TF-IDF Vectorization:** The plot summaries are transformed into numerical vectors using TF-IDF, capturing the importance of each word in the context of the entire dataset.

### 3. Clustering
- **K-Means Clustering:** Movies are clustered into groups based on their plot similarities using K-Means clustering.
- **Hierarchical Clustering:** A dendrogram is created to visually represent the hierarchical relationships between movies.

### 4. Dendrogram Visualization
- **Linkage Matrix:** A linkage matrix is computed to represent the similarity distances between movies.
- **Dendrogram Plot:** A tree-like diagram is plotted to show the hierarchical clustering results.


## Interactive Component

### Interactive Movie Similarity Finder

An interactive panel is provided for exploring movie similarities based on user input. The panel allows users to:

- **Select a Movie:** Choose a movie from a dropdown list of titles.
- **Specify Number of Similar Movies:** Use a slider to select the number of similar movies to display.
- **View Results:** The panel updates to show a list of movies similar to the selected movie based on plot similarity.

## Conclusion
This analysis provides insights into the relationships between movies based on their plot summaries. The interactive component enhances user experience by allowing real-time exploration of movie similarities. 
This project demonstrates the power of text processing and clustering techniques in uncovering hidden connections between movies.
