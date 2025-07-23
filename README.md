

## Overview

How does Amazon know I was interested in a bed sheet I had already in my Walmart.com cart? Why do I keep getting similar ads across platforms? This practice is called personalized advertising, where online ads promote the products and services their customers will be most interested in, to make profit. Instagram, for instance, is a social media platform that implements this personalized advertising algorithm to persuade their users to remain for a prolonged period of time on the site and guarantee a sale. This is conducted by collecting data on user interaction, such as searched keywords, number of likes on a post, comments, and number of shares.

The objective of this project is to understand & replicate the Instagram Personalized Advertisement algorithm within a Python environment by implementing a K-Means clustering based on user likings and interests.


This project simulates a dataset of fake social media users with attributes such as age, number of liked posts, and preferences across categories like sports, fashion, food, and pets. It uses statistical distributions to generate skewed data and creates realistic but synthetic user profiles using the `Faker` library.

The dataset is then analyzed and visualized to explore patterns such as the relationship between age and total likes, favorite categories by age groups, and user segmentation through clustering and PCA.

## Features

- **Data Generation:**  
  - Synthetic user ages generated using a skewed normal distribution to simulate realistic age demographics.  
  - Number of liked posts generated with high skewness to mimic user engagement distributions.  
  - Randomly assigned likes across multiple interest categories and subcategories.

- **Data Processing:**  
  - Aggregates likes into broader categories (sports, fashion, food, pets).  
  - Determines each user's top liked category and assigns age groups.

- **Visualization:**  
  - Histograms of age and liked posts distributions.  
  - Scatter plots showing user likes vs age and PCA principal components colored by top liked category.  
  - Elbow plot for selecting the optimal number of clusters.

- **Clustering & Segmentation:**  
  - Applies PCA for dimensionality reduction.  
  - Uses KMeans clustering on PCA-transformed data to segment users into distinct groups.

## Technologies Used

- Python 3.x  
- `numpy`, `pandas` for data manipulation  
- `scipy.stats` for statistical distributions  
- `matplotlib`, `seaborn`, `plotly` for visualizations  
- `faker` for generating synthetic user data  
- `scikit-learn` for PCA and KMeans clustering


